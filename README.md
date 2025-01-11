## Malbian Linux

Malbian Linux is a Debian-based GNU/Linux distribution aimed towards Malware Analysis and Reverse Engineering, created and maintained by [0xCambie](https://github.com/0xCambie).

The Firsts ISOs were made using [Penguins' Eggs](https://github.com/pieroproietti/penguins-eggs), a cool little utility created by pieroproietti.

The distributions run with custom scripts that would display information in a Tmux-session. What information? Useful information like Internet Conectivity, LAN IP Address, Target IP Address or Domain, VPN Connection status and Host connectivity state. The Xfce ISO consists of an Xfce Desktop Environment to provide a familiar user interface, while the DWM ISO runs with a Window Manager. They are both shipped with some general tools for Analyzing malware samples and simple system utilities in order to make the system more reliable and usable. 

I strongly recommend [installing](https://github.com/MalbianLinux/Malbian-ISOs) the Xfce version of Malbian since it's going to be less convoluted.

The project does not plan to have user support since at the moment I am the only maintainer, so a good Linux knowledge base is necessary to be able to troubleshoot your own problems.

This distribution is 100% free to use and distribute. This project was made in order to contribute to the community while also helping those who are starting with MA & RE. Also, it's important to give back to the internet all the help and knowledge that it gave us. 

### Why debian?

Simply because the system needs to be robust and work without being updated constantly since during malware analysis sessions the system will be isolated from the net. A Debian based distro also helps us ship stable ISO images that will not decay so quickly over time this helps prevent the need of weekly updates making a little bit easier to maintain and keep clean.
