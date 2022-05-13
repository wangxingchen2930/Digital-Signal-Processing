# Fast Fourier Transform

Fast version of DFS, which is implemented widely in computer.

The FFT result of a real signal is symmetric. Thus, the second half of the output will usually be discarded. But the FFT result of a complex signal is asymmetric. The negative part have its owen meaning in physical world and fftshift() is required for put negative part to correct place,

There are two spectrum in frequency domain:
- amplitude spectrum
- phase spectrum

The output and input of FFT have same dimensions,

FFT basically is used for analyzing the phase change $\Delta\theta$, where $\theta = \omega{t} + \phi_0$. The change can be caused by variant $t$ or $\Delta\phi_0$. While FFT usually is used for capturing $\omega$ of original signal. The difference among variant initial phases $\phi_0$ of one FFT result can also be used for capturing another dimension information (which cannot be captured by $\omega$ due to limited resolution) by using another FFT based on the first FFT result. Example: FMCW radar,