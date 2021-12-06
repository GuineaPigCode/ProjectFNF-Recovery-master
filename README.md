# Friday Night Funkin Recovery
* Engine: Project Engine
* VersionMOD: 0.5.8
* Version: 0.2.7.1
# Installing the Required Programs
https://github.com/ninjamuffin99/Funkin#friday-night-funkin

# Compiling game
NOTE: If you see any messages relating to deprecated packages, ignore them. They're just warnings that don't affect compiling

Once you have all those installed, it's pretty easy to compile the game. You just need to run lime test html5 -debug in the root of the project to build and run the HTML5 version. (command prompt navigation guide can be found here: https://ninjamuffin99.newgrounds.com/news/post/1090480) To run it from your desktop (Windows, Mac, Linux) it can be a bit more involved. For Linux, you only need to open a terminal in the project directory and run lime test linux -debug and then run the executable file in export/release/linux/bin. For Windows, you need to install Visual Studio Community 2019. While installing VSC, don't click on any of the options to install workloads. Instead, go to the individual components tab and choose the following:

1. MSVC v142 - VS 2019 C++ x64/x86 build tools
2. Windows SDK (10.0.17763.0)

Once that is done you can open up a command line in the project's directory and run lime test windows -debug. Once that command finishes (it takes forever even on a higher end PC), you can run FNF from the .exe file under export\release\windows\bin As for Mac, 'lime test mac -debug' should work, if not the internet surely has a guide on how to compile Haxe stuff for Mac.

# Credits 

FNF Recovery Team (LOL Only me)
* GuineaPigCode - Programmer

FNF Whitty Team
* Kade Dev - Programmer
* @Nate Anim8 - animation help, charting
* sock.clip - Musician, Main Animator

FNF Sky Team (Only 1)
* bbpanzu

Original Creators The Friday Night Funkin
* ninjamuffin99 - Programmer
* PhantomArcade3K and Evilsk8r - Art
* Kawaisprite - Musician
