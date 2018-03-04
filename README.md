# Piano_AnalysisSynthesis_FirstTry

I want to see if I can build a piano sampler in Python. I want to take a recording of a single piano note, run a Fourier analysis on it to determine its spectrum, and then synthesize an audio wave by applying the Fourier coefficients to sinusoids. I think that is called a Fourier Representation. If I get a meaningful result, then I want to extend that Fourier Representation to neighboring pitches and see how far I can go from the original pitch and still sound credble.

I use tools from Allen Downey's book about digital signal processing, Think DSP. His code is available on GitHub.

https://github.com/AllenDowney/ThinkDSP.

The piano sample comes from a Steinway B-211 sampled by KaleidonKep99 on GitHub.

https://github.com/KaleidonKep99/Steinway-B-211
