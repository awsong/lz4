lz4
===

LZ4 de/compresor for Golang

Speed on Intel G1610:<br>
Compresion: 209 MB/s, about 60% of C version speed<br>
Decompresion: 360 MB/s, about 20% of C version speed

If you'd like to run the benchmark through "go test -bench ." please download the Silesia corpus from [here](http://sun.aei.polsl.pl/~sdeor/corpus/silesia.zip). Unpack the files and concatinate them into one file named combined.bin.
