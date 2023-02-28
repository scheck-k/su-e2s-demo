# Demo Page for: Multi-speaker Speech Synthesis from Electromyographic Signals by Soft Speech Unit Prediction

Authors: Kevin Scheck, Tanja Schultz (Cognitive Systems Lab, University of Bremen, Germany)

Accepted at ICASSP 2023

### Speech-Unit-based EMG-to-Speech

Conventional Electromyography-to-Speech (E2S) models convert Electromyography (EMG) signals to  acoustic speech features, such as mel-spectrograms.
In this work, we predict content representations of Voice Conversion (VC) models instead.
For Speech-Unit-based EMG-to-Speech (SU-E2S), we predict soft speech units of the system of van Niekerk et al. (2022).
We use the [HuBERT-soft](https://github.com/bshall/soft-vc) encoder to extract soft speech units of the acoustic speech target and predict soft units with an EMG encoder.
We furthermore train a multi-speaker acoustic decoder, which processes soft speech units and a speaker embedding. 
As such, our model can perform multi-speaker E2S i.e. output the speech in a voice of another taret speaker.
We hope that we can leverage multi-speaker E2S for voice reconstruction in future work.

### Link to the paper: Following soon
