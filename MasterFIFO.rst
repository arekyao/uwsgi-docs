The Master FIFO
===============

Available commands:

* 'b' re-bind unix sockets
* 'c' trigger chain reload
* 'f' re-fork the master
* 'l' reopen log file (need --log-master and --logto/--logto2)
* 'L' trigger log rotation (need --log-master and --logto/--logto2)
* 'p' pause/resume the instance
* 'q' gracefully shutdown the instance
* 'Q' brutally shutdown the instance
* 'r' send graceful reload
* 'R' send brutal reload
* 's' print stats in the logs
* 'w' gracefully reload workers