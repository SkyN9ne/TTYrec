### TTYrec 

* ```ttyrec``` is a TTY recorder. * ```ttyplay``` is a TTY player.

## Installation:

```make```

or if your system is an SVR4 system (Solaris etc.)

  ```make CFLAGS=-DSVR4```

or if your system supports ```getpt(3)```

  ```make CFLAGS=-DHAVE_getpt```

```HAVE_getpt``` is required if your Linux system uses ```devfs```.


## Usage:

   ```ttyrec```
  (In the excuted shell, do whatever you want and exit)

   ```ttyplay ttyrecord```

Have fun!

-- Satoru Takabayashi <satoru@namazu.org>
