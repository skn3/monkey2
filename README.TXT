

***** Welcome to Monkey2! *****

Emscripten support is currently WIP.

Android and iOS support are currently MIA (but on the way).

The Ted2 IDE is currently very minimal. If you find it a little *too* minimal, a package for integrating monkey2 with 
Sublime Text 3 is available here: http://monkey2.monkey-x.com/forums/forum/general-programming-discussion/


***** Building monkey2 on Windows *****

1) Install the mingw-64 compiler. Mingw-64 is available here: 

https://sourceforge.net/projects/mingw-w64/

When installing, you should select 'i686' for 'architecture', 'posix' for 'threads' and 'dwarf' for 'exception'.

There is also a self-extracting archive of mingw-64 that has been tested with monkey2 here:

http://www.monkey-x.com/mak/devtools/i686-5.3.0-posix-dwarf-rt_v4-rev0.exe

If you install this to the monkey2 'devtools' directory, the following steps should 'just work'.

2) Open a command prompt and change to the 'monkey2\scripts' directory.

3) Enter 'rebuildall' and hit return. Wait...

4) If all went well, you should end up with a 'Monkey2 (Windows)' exe in the monkey2 directory.

5) You should now be able to build and run monkey2 apps. There is a simple 'hello-world.monkey2' test in the monkey2 
directory, and some simple demos in the '/bananas' directory.


***** Building monkey2 on MacOS/Linux *****

1) On MacoS, install the xcode command line tools. You can do this by entering 'xcode-select --install' in a shell.

2) Open a shell and change to the 'monkey2/scripts' directory.

3) Enter './rebuildall.sh' and hit return. Wait...

4) If all went well, you should end up with a 'Monkey2 (...)' app in the monkey2 directory.

5) You should now be able to build and run monkey2 apps. There is a simple 'hello-world.monkey2' test in the monkey2
directory, and some simple demos in the '/bananas' directory.


***** More information *****

Monkey2 patreon page: https://www.patreon.com/monkey2?ty=h

Monkey2 development blog: http://monkey2.monkey-x.com/

Monkey2 development forums: http://monkey2.monkey-x.com/forums

Monkey2 xmas 2015 demo: http://monkey2.monkey-x.com/2015/12/23/xmas-demo-2015/
