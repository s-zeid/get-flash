get-flash
=========

A Python 3 script that downloads the latest PPAPI Flash plugin directly from
Adobe.

Copyright (c) 2014, 2016 [Scott Zeid](https://s.zeid.me/).  
Released under [the X11 License](https://tldrlegal.com/l/x11).  
<https://code.s.zeid.me/get-flash>

[**Download**](https://code.s.zeid.me/get-flash/raw/master/get-flash)


Usage
-----

    usage: get-flash [-h] [-a {x86_64,i686}] [-o OUTPUT_TO] [-e EXTRACT_TO]
    
    Downloads the latest PPAPI Flash plugin directly from Adobe.
    
    optional arguments:
      -h, --help            show this help message and exit
      -a {x86_64,i686}, --arch {x86_64,i686}, --architecture {x86_64,i686}
                            download for the given architecture
    
    at least one of the following is required:
      -o OUTPUT_TO, --output OUTPUT_TO
                            save the archive to the given filename or directory
      -e EXTRACT_TO, --extract EXTRACT_TO
                            extract the archive to the given directory (will be
                            created if necessary)
