State machine for reading a file containing audio data and splitting into individual tracks based where the long runs of close-to-zero values (the silence between tracks) are. Will output the timestamps of the beginning and end of each track.

The name of the input file is hard-coded as `audio.dat`, so copy one of the data files to that before running.

This version has debugging output so you can see the changes to state and other variables as the program reads data.

There is some code to translate the index within the file to timestamps measures in seconds; that code is not important to understanding the behavior of the state machine.
