# Haskell-Leksah
Development Work on using Haskell GHC Compiler and Leksah Haskell GUI IDE

Setup Environment
:~/apps/leksah$ uname -a
Linux HP-EliteBook-8470p 4.4.0-92-generic #115-Ubuntu SMP Thu Aug 10 09:04:33 UTC 2017 x86_64 x86_64 x86_64 GNU/Linux

:~/apps/leksah$ ./leksah.sh
Sat Aug 19 01:16:54 MYT 2017 (1/12) Bismillah WRY starting leksah Haskell GUI
Sat Aug 19 01:16:54 MYT 2017 (1.1) LEKSAH_SERVER_VERSION=0.16.2.0
Sat Aug 19 01:16:54 MYT 2017 (1.2) LEKSAH_VERSION=0.16.2.2
Sat Aug 19 01:16:54 MYT 2017 (1.3) GHCVER=8.2.1
Sat Aug 19 01:16:54 MYT 2017 (1.4) DIR=/home/wruslan/apps/leksah
Sat Aug 19 01:16:54 MYT 2017 (1.5) OS=linux
Sat Aug 19 01:16:54 MYT 2017 (1.6) ARCH=x86_64
Sat Aug 19 01:16:54 MYT 2017 (2/12) CHECK CABAL VERSION: Using Cabal 2
Sat Aug 19 01:16:54 MYT 2017 (2.1) WHICH CABAL = /home/wruslan/.cabal/bin/cabal
Sat Aug 19 01:16:54 MYT 2017 (2.2) CABAL VERSION = cabal-install version 2.0.0.0
compiled using version 2.0.0.2 of the Cabal library 
Sat Aug 19 01:16:54 MYT 2017 (3/12) CHECK GHC COMPILER VERSION: Using /home/wruslan/apps/ghc-8.2.1/bin/ghc
Sat Aug 19 01:16:54 MYT 2017 (3.1) WHICH GHC = /usr/bin/ghc
Sat Aug 19 01:16:54 MYT 2017 (3.2) GHC VERSION = The Glorious Glasgow Haskell Compilation System, version 8.2.1
....
Sat Aug 19 01:16:54 MYT 2017 (6/12) RUNNING 1/3 cabal new-configure --with-ghc='/home/wruslan/apps/ghc-8.2.1/bin/ghc-8.2.1' 
Sat Aug 19 01:16:54 MYT 2017 (6.1) Executing ...
....
Sat Aug 19 01:16:55 MYT 2017 (7/12) RUNNING 2/3 cabal new-build ....
Sat Aug 19 01:16:55 MYT 2017 (7.1) Executing ...
....
Sat Aug 19 01:21:17 MYT 2017 (8/12) RUNNING 3/3 set path and run leksah GUI ...
Sat Aug 19 01:21:17 MYT 2017 (8.1) Executing ...
....
Sat Aug 19 01:21:17 MYT 2017 (9/12) ALHAMDULILLAH. NOW WE ARE RUNNING LEKSAH GUI ....at (git cloned) /home/wruslan/apps/leksah
Sat Aug 19 01:21:17 MYT 2017 (9.1) Executing ...
Using default Yi configuration
Linked with -threaded
Reading keymap from /home/wruslan/apps/leksah/data/keymap.lkshk
Now updating system metadata ...
callCollector
leksah: FileUtils>>getSysLibDir failed with ghc-8.2.1: createProcess: runInteractiveProcess: exec: does not exist (No such file or directory)
CallStack (from HasCallStack):
  error, called at src/IDE/Utils/FileUtils.hs:428:35 in leksah-server-0.16.2.0-inplace:IDE.Utils.FileUtils

WE HAVE AN ERROR.
Wassalam.
WRY

Same error as reported at https://github.com/leksah/leksah/issues/428

:~/apps/leksah$ ls -al /home/wruslan/apps/leksah/dist-newstyle/build/x86_64-linux/ghc-8.2.1/leksah-0.16.2.2/c/leksah/build/leksah/
total 169980
drwxr-xr-x 4       4096 Aug 19 01:21 .
drwxr-xr-x 3       4096 Aug 19 01:21 ..
drwxr-xr-x 2       4096 Aug 19 01:21 autogen
-rwxrwxr-x 1  174041856 Aug 19 01:21 leksah      <=== Successfully built (174 MB) compiled. 
drwxr-xr-x 2       4096 Aug 19 01:21 leksah-tmp
:~/apps/leksah$ 

