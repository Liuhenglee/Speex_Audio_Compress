# Speex_Audio_Compress

Introduction:

A project based on the speex 1.2rc1 project, some bugs have been fixed.

Runs on visual studio and can convert wav to and from SPX files.

Additional note:

Developers have added libogg and speex from the open source library integrator Vcpkg to Visual Studio.

Some error may be reported when the library in Vcpkg is not added.



To use the Speex command line tools:

% speexenc [options] input_file.wav compressed_file.spx

% speexdec [options] compressed_file.spx output_file.wav



Examples to use:

./speexenc --quality 8 ../../wavetest_for_speex.wav ../../wavetest_for_speex.spx

./speexdec ../wavetest1_spx_8.spx ../../wavetest_rev.wav