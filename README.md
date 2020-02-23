This is an unofficial developer tool repository that holds some tools to make development of modules and scripts easier in libra.

Files:
transport.sh - expects libra to be installed in Users/[username]/home/libra and the transport file to be place in the module development directory. The script moves the module, test from current directory to libra testsuite/custom:modules directory and runs the test commande. This makes it easier to place your workoing directory anywhere outside the libra root.


To do:
- Gas estimater for modules and scripts.
