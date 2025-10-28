# Sviluppo di un sistema embedded per il controllo della temperatura in un camera di collaudo.

Il sistema embedded si occupa di controllare la frequenza di una ventola di raffreddamento tramite un controllo PID (tramite protocollo MODBUS RTU) e di fornire un interfaccia per regolare la temperatura target della stanza tramite display touchscreen. La GUI e programmata con la libreria LVGL.

Il sistema embedded e' collegato alla rete aziendale tramite ethernet e tramite un web server sara possibile regolare la temperatura target anche da remoto.

La comunicazione tra sistema embedded e web server avviene attraverso scrittura su file/IPC.

E ancora da valutare se verra utilizzato un database per loggare la temperatura nel tempo. Nel caso il web server si occupera di interagire con esso.

Il lavoro verra principalmente svolto in autonomia con supervisione da parte da parte del tutor aziendale.

Al momento il controllo della temperatura nella stanza e effettuato manualmente e questo sistema automatizzerebbe il tutto.