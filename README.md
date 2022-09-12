# Grms-calculation-Vibration-analysis

Grms is mean acceleration about any axis.<br />

The data used was taken from imu sensor along z axis.<br />
To calculate Grms:<br />
1st normalize acc data<br />
2nd plot time vs acc data<br />
3rd calculate FFT <br />
4th generate PSD curve and calculate area<br />


note:<br />
The Fourier Transform is used to convert a time varying signal waveform into a frequency varying signal waveform. That is, given a Time Domain signal representation, a Fourier Transform will convert that representation into a Frequency Domain representation.
The power spectral density is equal to the integral of the signal squared, regardless of whether your signal waveform is expressed in the time domain, or the frequency domain.
But, the advantage of using the frequency domain representation is that you can then consider the power distribution, or power contributed by each frequency spectra.
