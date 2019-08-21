Installing LibertyBSD

You can download a bootable CD image of LibertyBSD at this website:
http://libertybsd.net/



Go to the downloads section:


Click on it, then you will see this text:








Click on “Download LibertyBSD 5.9 here”



Then you will see this page:


Select the right folder that correspond with the CPU architecture of your PC

For example:

For Intel 64bit CPU's select:	amd64
For older 32bit CPU's select:	i386

In this example I will install LibertyBSD on a Intel Core i5 processor, so I choose: amd64 




Select from the list the install59.iso file 
and download this file to your computer. (for example to the Downloads folder)

Important!
To make sure that the file is not tempered with, you should always verify your download! And check if the file is not corrupt and that it's original.
You can easily do this by downloading the checksum SHA256 file, that also located in this directory.



Download the SHA256 and SHA256.sig file to your computer. 
(for example to the Downloads folder)


Then start a terminal on your computer, and go to the folder were you downloaded
the install59.so, SHA256 and SHA256.sig files

In this example:   cd Downloads






Then type:  sha256sum install59.iso



The answer is:
1244e15ca35ee967f7f44da8bbe0240ce086c3287ecc81f3df26e80c2d3a966d
This long line is called a hash (it's a alphanumeric string)



Then we have compare this hash, if it's the same then printed in the file:
SHA256




To do this go to your file manager:






Open the “SHA256” file with “gedit” (by double clicking it)



Locate the hash of the “install59.iso”



The hash in the text is:

1244e15ca35ee967f7f44da8bbe0240ce086c3287ecc81f3df26e80c2d3a966d

The hash from the terminal after typing sha256sum install59.iso was:

1244e15ca35ee967f7f44da8bbe0240ce086c3287ecc81f3df26e80c2d3a966d


These two hashes are identical, and this is good, so now we know that the iso
is correctly download, not corrupt and has not been tempered with.

No we can proceed with the installation steps












Burn the “install59.iso” on a CD

Put an empty CD-R in your CDROM writer of your computer

Start your cdwriter software

For example “K3B”








Go to “Tools” - “Burn image...” 





You will see this screen






















After burning the “install59.iso” to CD, place the CD in the CDROM player of the computer were you want install LibertyBSD on.

Important:
All data will be erased of your computer by following the instructions of this manual, so if you want to make a backup do it now!
