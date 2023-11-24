# videoplayback_gst_sample_appln
sample video playback gstreamer application which demonstrate the test video data display using autovideosink


Dependency Environment details:
==============================================================================================================

Linux Ubuntu Machine used for application execution.

# lsb_release -a

No LSB modules are available. Distributor ID: Ubuntu Description: Ubuntu 18.04.4 LTS Release: 18.04 Codename: bionic

# uname -r

4.15.0-99-generic



Install gstreamer related package on ubuntu OS:
=============================================================================================================


https://gstreamer.freedesktop.org/documentation/installing/on-linux.html?gi-language=c

apt-get install pkg-config sudo apt-get install libgstreamer1.0-dev




Application compilation command:
=============================================================================================================

# gcc -Wall videotestfeedappln.c -o videoplaybackapplnexe $(pkg-config --cflags --libs gstreamer-1.0)



Application execution run command:
=============================================================================================================

# ./videoplaybackapplnexe

Running ...

once execution started, then OpenGL renderer window will display the video test pattern data.
go to terminal where the execution running, press ctrl+C to kill the application.




Primary Reading: 
==============================================================================================================
GObject instantiation

GObject properties(set/get)

GObject casting

GObject referencing/dereferencing

glib memory management

glib signals and callbacks

glib main loop