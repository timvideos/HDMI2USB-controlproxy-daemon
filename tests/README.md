Building and running the tests requires the googetest suite 1.7+, which
should be placed in ${hdmi2usbd_root}/tests:

    $ cd tests
    $ git clone https://github.com/google/googletest

Running the unit tests:

    With cmake 3.x installed, do:

        $ cd build
        $ cmake -Dtests=ON ..

    Build with 'make' (on Unixish systems)

        $ make

    Unit test executables are built in the same directory with names
    starting with 'run'
