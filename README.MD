## gnu-slash-grub
Fix GRUB boot menu nonsense

TL;DR it swaps 'Linux' with 'GNU/Linux' and removes the extra 'Linux' where it's not needed. RMS approved. :thumbsup:

(take a look inside extra/example to see what actually happens)
 
There's also a pacman hook inside extra for running this program whenever grub is updated or (re)installed.
