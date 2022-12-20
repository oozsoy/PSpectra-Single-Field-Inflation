## SingleFieldINF_Powerspec

We provide two seperate (pedagogical) Jupyter notebook file that computes the power spectrum of curvature perturbation:

- In canonical single field inflationary scenarios that include a transient phase of non-attractor era required for the amplification of the spectrum.
- In generalized single field inflationary models that exhibit an effective time dependent Planck mass along with a non-trivial sound speed for the scalar fluctuations.

For the purpose described above, the background an effective parametrization of the background evolution is provided following arXiv: XXXX.XXXX. Around this background solution, we then solve the Mukhanov-Sasaki (MS) equation for each mode in Fourier space which is essential for the computing the power spectrum of scalar fluctuations during inflation. 

The program can be generalized to include a user defined scalar potential: by adding an initial section that computes the background equations for a given scalar potential $V(\phi)$ followed by defining the relevant background / slow-roll parameters required for the solution of the MS equation. 
