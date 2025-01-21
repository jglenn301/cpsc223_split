State machine for reading a file containing audio data and splitting into individual tracks based
where the long runs of close-to-zero values (the silence between tracks) are.
Will output the timestamps of the beginning and end of each track.

The name of the input file is hard-coded as audio.dat, so copy one of the data files to that before running.
