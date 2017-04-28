# MusicVisualizer (or MV)

## What is MV?
MusicVisualizer is a project written in Python that visualizes mp3s and outputs
mp4 videos.  This is currently in alpha development but is showing promise,
executing it's main goal of visualizing music.

## Installing
Currently our install script ain't perfect. First, make sure you have `pip3`
installed with

    sudo apt-get install python3-pip    # Get pip3
    sudo pip3 install numpy             # Numpy has to be installed seperately
    sudo setup.py install               # Run the install script

You should be good (hopefully).

## Running
There are two ways to run MV; the first is through a command line interface, and
this gives you the maximal flexibility. The second is through the GUI and this
gives restricted access.

### Running From Command Line
Assuming that we installed everything correctly, we can run `visualize
input.mp3` and after some crunching an `output.mp4` will appear in the directory
that you called `visualize` from. Additonally you can pass an output argument
`-o path/to/destination/file.mp4` to specify where you would like the output to
end up. For more information run `visualize --help`.

### Running from GUI

