# mm-unicode-guide-for-Linux
This is Myanmar Unicode Installation Guide for Linux

# Keymagic
  Download ibus-keymagic and install it\
  sudo dpkg -i ibus-keymagic*.deb

# Keyboard Layout
  Download Pyidaungsu MM.km2\
  mkdir ~/.keymagic\
  cp -r .km2 ~/.keymagic\
  ibus-daemon -rdx\
  ibus-setup &\
  ibus-daemon -rdx
  
# Fonts  
  Download and install Pyidaungsu font

# Acknowledgement
https://github.com/thantthet/keymagic \
https://sourceforge.net/projects/ubuntumm/files/ibus-keymagic/ \
https://keymagic.net/installation/linux/ \
https://github.com/kokoye2007/ibus-keymagic \
https://github.com/naingyeminn/mm-kb
  
