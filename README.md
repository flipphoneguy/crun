#crun

just a wrapper to automate compiling and running c on termux.

normally if your device isn't rooted you'd have to copy your c script to termux home, compile it, change the outputs permission and then run it. this file automates all that by you just running crun followed by the filepath to the c script you want to run. for more details, after setting it up run 'crun -h'

prerequisites:
- termux installed
- clang installed in termux ('pkg install clang')

setup:
- in termux run 'cp /path/to/crun $BIN'
- then just run 'chmod +x $BIN/crun'

###That's it! You can now run 'crun -h' to ensure its working.

credits: flipphoneguy