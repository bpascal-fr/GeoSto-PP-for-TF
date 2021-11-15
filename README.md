# GeoSto-PP-for-TF
Tutorial of the mini-course on  
*Point processes for time-frequency analysis*  
B. Pascal & R.Bardenet

Point processes in the plane or the space have been major statistical models for spatial data in signal processing, from seismology to telecommunications. They come with an arsenal of exploration and inference
tools, known as spatial statistics. Starting in 2015, point processes have also appeared in a more indirect
way in signal processing, not as a statistical model for observed data, but as a natural way to describe
and process nonstationary signals in the time-frequency plane.
More precisely, consider linear “time-frequency” transforms from the space of finite energy signals f to spaces of analytic functions,
such as the Gabor transform. The Gabor transform sends a one-dimensional signal, say a function f of
time like an audio recording, onto a function of a complex argument, the real part of which is interpreted
as time, and the imaginary part as frequency. The modulus of that complex function is known as a
spectrogram, and is to be read as the “musical score” of the initial signal f, with a large value of the
spectrogram at a given time and frequency being akin to a musical note on a score. Many signal processing
algorithms revolve around identifying regions in the complex plane where the spectrogram is significantly
large. In contrast, zeros of the spectrogram indicate perfect silence, a time at which a particular frequency
is absent. Being the zeros of an analytic function, and actually a random analytic function if the input
signal f is considered random, these zeros form a point process in the complex plane. This tutorial is
devoted to such point processes arising as the zeros of time-frequency transforms of random signals, to
their links to the rich research around zeros of Gaussian analytic functions, and to how spatial statistics
can yield signal detection and denoising algorithms that rely on identifying perturbations in the (point)
pattern of silence.

## Stochastic Geometry days,  
November 15th-19th, 2021, Dunkerque
