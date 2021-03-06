### DCTNet and ADCTNet
#### This file contains MATLAB codes that generate audio DCTNet feature. This work has been shown in the paper: Adaptive DCTNet for Audio Signal Classification, and PCANet and DCTNet for Acoustic Signals Feature Extraction.
##### It has been published by the Journal of Acoustical Society of America and the International Conference of Acoustic and Speech Signal Processing (ICASSP) 2017.

##### About the codes:
##### 1. "bird_song_example" folder contains 4 bird song wav file, ADCTNet and DCTNet feature code. 
##### "ADCTNet_demo.m" is a MATLAB demo file to generate bird song ADCTNet feature.
#### 2. "handel_example" folder contains codes to generate 2-layer ADCTNet and DCTNet feature for Handel's "Messiah" in MATLAB.
##### "ADCTNet_music_demo.m" is a MATLAB demo file to generate music ADCTNet feature, 
##### "dctnet_music_demo.m" is a file to generate music dctnet feature. "stdct.m" is the short time DCT function.
#### 3. "plot_in_paper" folder contains MATLAB codes to generate ADCTNet, DCTNet, MFSC, LFSC, ERB-rate and scattering transform feature, and a data .mat file. 
##### "ADCTNet_paper_demo.m" is a MATLAB demo file to generate music ADCTNet feature,
##### "dctnet_demo.m" is a file to generate music dctnet feature. "stdct.m" is the short time DCT function.
##### "comparison2_feature.m" generates features for comparison: MFSC, LFSC, ERB-rate and scattering transform.
#### This folder can generate figures appeared in papers: "Adaptive DCTNet for Audio Signal Classification" (https://arxiv.org/abs/1612.04028), "DCTNet and PCANet for Acoustic Signal Feature Extraction" (https://arxiv.org/abs/1605.01755).
#### To generate MFSC, LFSC, ERB-rate features for comparison, we need voicebox MATLAB toolbox (http://www.ee.ic.ac.uk/hp/staff/dmb/voicebox/voicebox.html). 
#### To generate scattering transform feature, we need scatnet MATLAB toolbox (http://www.di.ens.fr/data/software/scatnet/quickstart-audio/). 
