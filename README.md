# Kickstart File
A Kickstart file is a plain text file used to automate the installation of Red Hat Enterprise Linux (RHEL), Fedora, CentOS, and compatible systems. 
It contains a predefined list of commands and parameters that provide all the necessary answers to the questions normally asked during a manual installation, 
such as time zone, partitioning, and package selection.

### Usage and Creation
Manual Installation: The most common method is to perform one manual installation. All the choices made are saved to a file named anaconda-ks.cfg in the /root/ directory of the installed system, which can then be copied and modified.
Configuration Tools: You can use an online Kickstart configuration tool available on the Red Hat Customer Portal or other third-party generators.
Manual Creation: The file is a simple ASCII text file and can be created from scratch using any text editor (like vim or notepad) by following the specific syntax reference.
