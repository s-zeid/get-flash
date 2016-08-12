get-flash
=========

A Python 3 script that downloads and extracts the latest PPAPI Flash plugin
directly from Adobe.

Copyright (c) 2014, 2016 [Scott Zeid](https://s.zeid.me/).  
Released under [the X11 License](https://tldrlegal.com/l/x11).  
<https://code.s.zeid.me/get-flash>


Usage
-----

    usage: get-flash [-h] -o OUTPUT [-A {x86_64,i686}]
    
    Downloads and extracts the latest PPAPI Flash plugin directly from Adobe.
    
    optional arguments:
      -h, --help            show this help message and exit
      -o OUTPUT, --output OUTPUT
                            (required) the directory to which to extract the
                            archive (will be created if necessary)
      -A {x86_64,i686}, --arch {x86_64,i686}, --architecture {x86_64,i686}
                            download for the given architecture
