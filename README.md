# Meteor-M2 Demodulator

This is a free, open-source LRPT demodulator for the Meteor-M2 Russian weather
satellite. It supports reading from a I/Q recording in .wav format,
and it outputs an 8-bit soft-QPSK file, from which you can generate an image
with the help of LRPTofflineDecoder or
[meteor\_decoder](https://github.com/artlav/meteor_decoder).

# Compling and installing

As usual, type `make` to compile the package, `make install` to install the
binary to /usr/bin/. A `debug` target is available if you want to keep the debug
symbols in the executable.
