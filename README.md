## SingleFieldINF_Powerspec

We provide two seperate (pedagogical) Jupyter notebook files that compute the power spectrum of curvature perturbation,

- In canonical single field inflationary scenarios that include a transient phase of non-attractor era: *PowerSpec_CanonicalSF.ipynb*
- In generalized single field inflationary models that exhibit an effective time dependent Planck mass along with a non-trivial sound speed for the scalar curvature fluctuations: *PowerSpec_GSF.ipynb*

For the former, an effective (but accurate) parametrization of the background evolution is adopted where inflationary evolution has been modeled in terms of successive phases of slow-roll --> non-attractor --> slow-roll: see arXiv: 2301.03600 for details. Around this background solution, we then solve the Mukhanov-Sasaki (MS) equation for each mode in Fourier space which is essential for the computing the power spectrum of scalar fluctuations during inflation. 

The program can be generalized to include a user defined scalar potential: by *e.g* adding an initial section that computes the background equations for a given scalar potential $V(\phi)$ followed by defining the relevant background / slow-roll parameters required for the solution of the MS equation. 

***

For the latter, similarly to the canonical single field case, we adopt a phenomenological background model that exhibit a transient/localized slow-roll violation during inflation where the sound speed $c_s$ , effective time dependent Planck Mass $M$  and $\epsilon$ are all engineered to have a localized simultaneous dip.

The mode evolution in this case is determined by the generalized Mukhanov-Sasaki equation. Further details regarding the background and the mode evolution within the generalized single field models can be found in arXiv: [1811.03065](https://arxiv.org/abs/1811.03065) and 2301.03600 

For any queries, please contact:
[ogan.ozsoy@csic.es](ogan.ozsoy@csic.es)
