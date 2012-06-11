Wheel easy install
==================
Ok this isnt super easy but if you have vagrant installed then this cannot get much easier.

Requirements
------------
* [Virtual Box](https://www.virtualbox.org/ "VirtualBox")
* [Vagrant](http://vagrantup.com/ "Vagrant")

Running
-------
* Clone the project wherever you like.
* open cmd or terminal (depending on your OS, I use Cygwin on windows)
* cd into the vagrant folder that came with the project
* run "vagrant up"
* once vagrant and puppet have finished doing their work you should be able to see wheel running on [http://10.0.0.2](http://10.0.0.2 "default host only address")

If your feeling really lazy
---------------------------
use the script below to get the project checked out and running
```bash
#mkdir and cd into that directory first please!
git clone git://github.com/SnatchFrigate/Wheel-Easy-Install.git .
cd ./vagrant
vagrant up
```
