# Digital Up Converter and Digital Down Converter

## Baseband signal modulation

Any signal in physical world is real numbers.

Use complex number during computation in computer for convenience.

If real signal is used as baseband signal, half of frequency band will be wasted (real signal is symmetric in frequency domain). Therefore, we use complex number as baseband signal. Then it will carry double information compared to real signal:

$$ I(t) + jQ(t) $$

In computer, we just calculate multiplication of complex signal

## Why we need DUC and DDC?

The length of antenna need to be in the same order compared to wavelength of signal to be transmitted. So high-frequency carrier signal is necessary.  