# ARGUMENTS

Command line arguments passed to SCons.

    scons
    ./main.out
    # => 0
    scons x=1
    ./main.out
    # => 1
    scons x=0
    ./main.out
    # => 0
