# Image-Compressed-Sensing-using-Convolutional-Neural-Network
In Traditional image acquisition, the analog image is first acquired using a dense
set of samples based on the Nyquist-Shannon sampling theorem, of which the
sampling ratio is no less than twice the bandwidth of the signal, then compress the
signal to remove redundancy by a computationally complex compression method
for storage or transmission.

Compressive Sensing theory shows that a signal can be recovered from many
fewer measurements than suggested by Nyquist-Shannon Sampling theorem when
the signal is sparse in some domain.

We have Implemented a CS framework using Convolutional Neural Network
(CSNet) that includes a sampling network and a reconstruction network, which are
optimized jointly.

The sampling network adaptively learns the floating-point Sampling Matrix
from the training images, making the CS measurements retain more image
structural information for better reconstruction.

The reconstruction network learns an end-to-end mapping between the CS
measurements and the reconstructed images. It consists of an Initial
reconstruction network and a non-linear deep reconstruction network based
on residual learning. The reconstruction network can effectively utilize inter-block
information and avoid blocking artifacts.

