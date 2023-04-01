<h1> install packet tracer on arch </h1>
  
<h2>1. download the .deb file from netacad.com</h2>
<h2>2. Clone the packettracer install script from AUR</h2>

git clone https://aur.archlinux.org/packettracer.git


<h2>3. copy the .deb file to the directory of the script</h2>
<h2>make the .zst file by runing the script</h2>

makepkg

<h2>install the tar file with pacman</h2>
sudo pacman -U [packetTracer-file-name.tar.zst]
