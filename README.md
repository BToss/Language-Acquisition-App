# Language-Acquisition-App
New Github for the project. Problems came up when I ended up copying too many things and not needing them...
Will add better README soon.

# Sandeep,
take a look at that gradle nonsense and figure out how to connect three things together:
1: the audio coming into the phone
2: the kiss_fft files that are doing all the main work
3: adding a Gaussian window function and applying it to kiss_fft's output (see AudioAnalyzerHelperJNI.cpp for an idea of what it might look like.)
Check out: https://github.com/itdaniher/kissfft/blob/master/README
All I want is to write a windowing function that works on the fft data. I don't need a printout until much later in the app, when we've graphed vowels and shit, so display items are irrelevant in the final product. You might want them for testing, but they won't be needed at the end.
