# Neural dynamics of attentional modulation of macaque brains using neurofeedback techniques in an invasive cognitive brain-computer interface setup
The use of classification procedures to decode brain activity associated to specific aspects of human behaviour is the basis of brain-computer interface (BCI). Classically applied in motor-related activities, an increasing amount of evidence suggests the feasibility to develop BCI technologies relying on higher-order cognitive functions such as attention. In this context, prior studies have succeed in decoding the attentional spotlight (AS) with a high temporal resolution, allowing to understand the dynamics of the attentional system during its active engagement, but also to envision the development of neurofeedback (NF) approaches to increase attentional resources. In this context, we trained two macaques monkeys to perform a 100% validity cued endogenous attentional task while multiunit activity (MUA) was intra-cranially recorded from both Frontal Eye Fields. During the task performance, position of the AS was decoded in real-time and, when the AS was in the cued quadrant, a feedback was provided in form of a sensory information (sound) and reward (water intake). 
We found that attention position was encoded differently after the NF. Specifically, we observed that after NF the spatial prefrontal population code for attention changed dynamically during the cue-to-target interval, showing an alternation between a new code and the pre-NF code. We computed the frequency of this code alternation and we found that both codes systematically alternate within the theta (4-7Hz) band, which is associated with the learning of new contingencies. Interestingly, the phase of this oscillation accounted for significant variations in behavioural performance, suggesting that these NF-induced oscillations impact both function and behavior. 
These results demonstrate for the first time that (i) the application of attention-related NF modulates how the prefrontal cortex encodes information and (ii) these changes are a functional signature that accounts for behaviour. Altogether, our data envision the feasibility of the NF-based interventions in the attention domain with potential applications in healthy population or as a treatment for attention disorders.

## Time-resolved Results (Developed Toolbox)
* Cross/Within-temporal Spatial Decoding Map;
* Temporal Analysis:
  * Raw Accuracy Time-series;
  * Granger Causality Test.
* Spectral Analysis:
  * Auto/Cross-wavelet Power Spectral Density (PSD);
  * Coherence Spectral Analysis;
  * Granger Causality Spectral Analysis;
  * Phase Slope Index.
* Time-frequency Representation:
  * Auto/Cross-spectrogram;
  * Coherogram.
* Relative Phase Analysis:
  * From Cross-spectrogram;
  * From Cross-coherogram.
  
![](ppt/Instantaneous.gif)

## Cross/Within-Temporal Decoding Map PSD (Regular and Baseline-corrected) Computation, Visualisation and Statistical Test (Two/one-sided Wilcoxon Signed Rank Sum) for All Experimental Conditions and their Combinations (Developed Toolbox) 
![](ppt/PSD-GUI.gif)

## Cross/Within-Temporal Decoding Map PSD (Regular and Corrected Versions) Computation, Visualisation, Statistical Test (Two/one-sided Wilcoxon Signed Rank Sum), and Behavioural Analysis for All Experimental Conditions and their Combinations (Developed Toolbox) 
![](ppt/PSD-GUI2.gif)

## Statistical (Two-sided Wilcoxon Signed Rank Sum) Comparison of the Optimal Frequency, Phase, and Behavioural Performance between PreNF and PostNF, and Peak Frequencies Comparison Obtained from Behavioral and Electrophysiological Analyses in the User-Specified Frequecy-Of-Interest (FOI) (Developed Toolbox)
![](ppt/MUA-Behave-FOI.gif)

## The Effect of Class Balancing Techniques on the Cross/Within-Temporal Decoding Maps (Accuracy and True Positive Rate) (Developed Toolbox)
* Minimum;
* Synthetic Minority Oversampling Technique (SMOTE);
* BorderlineSMOTE;
* SafeLevelSMOTE;
* ADASYN.
![](ppt/CWTDM_AccTPR_detailed_balancing_.gif) 

## Significance of the Cross-wavelet PSD Peak Considering the Relative Phase Tested on Simulated Noisy (Different SNRs) Oscillatory (Different Frequencies) Time-series (Developed Toolbox)
![](ppt/NoisySignals_2Hz12.gif)
![](ppt/WaveletcrossPSD_2Hz12_.gif)

## Time-resolved Decoder (2D Regressor) Output
![](ppt/decoderOutput-10RptFast.gif)

## Binning Designer: Binning Parameters Effects on the Frequency Content of the Binned Signal
For further details, please visit [here](https://github.com/fardinafdideh/binning-designer).
![](ppt/all.gif)

## Exploratory Research on Non-human Primate Bio-signals
![](ppt/Diapositive1.PNG)
![](ppt/Diapositive2.PNG)
![](ppt/Diapositive3.PNG)
![](ppt/Diapositive4.PNG)
![](ppt/Diapositive5.PNG)
![](ppt/Diapositive6.PNG)
![](ppt/Diapositive7.PNG)
![](ppt/Diapositive8.PNG)
![](ppt/Diapositive9.PNG)
![](ppt/Diapositive10.PNG)
![](ppt/Diapositive11.PNG)
![](ppt/Diapositive12.PNG)
![](ppt/Diapositive13.PNG)
![](ppt/Diapositive14.PNG)
![](ppt/Diapositive15.PNG)
![](ppt/Diapositive16.PNG)
![](ppt/Diapositive17.PNG)
![](ppt/Diapositive18.PNG)
![](ppt/Diapositive19.PNG)
![](ppt/Diapositive20.PNG)
![](ppt/Diapositive21.PNG)
![](ppt/Diapositive22.PNG)
![](ppt/Diapositive23.PNG)
![](ppt/Diapositive24.PNG)
![](ppt/Diapositive25.PNG)
![](ppt/Diapositive26.PNG)
![](ppt/Diapositive27.PNG)
![](ppt/Diapositive28.PNG)
![](ppt/Diapositive29.PNG)
![](ppt/Diapositive30.PNG)
![](ppt/Diapositive31.PNG)
![](ppt/Diapositive32.PNG)
![](ppt/Diapositive33.PNG)
![](ppt/Diapositive34.PNG)
![](ppt/Diapositive35.PNG)
![](ppt/Diapositive36.PNG)
![](ppt/Diapositive37.PNG)
![](ppt/Diapositive38.PNG)
![](ppt/Diapositive39.PNG)
![](ppt/Diapositive40.PNG)
![](ppt/Diapositive41.PNG)
![](ppt/Diapositive42.PNG)
![](ppt/Diapositive43.PNG)
![](ppt/Diapositive44.PNG)
![](ppt/Diapositive45.PNG)
![](ppt/Diapositive46.PNG)
![](ppt/Diapositive47.PNG)
![](ppt/Diapositive48.PNG)
![](ppt/Diapositive49.PNG)
![](ppt/Diapositive50.PNG)
![](ppt/Diapositive51.PNG)
![](ppt/Diapositive52.PNG)
![](ppt/Diapositive53.PNG)
![](ppt/Diapositive54.PNG)
![](ppt/Diapositive55.PNG)
![](ppt/Diapositive56.PNG)
![](ppt/Diapositive57.PNG)
![](ppt/Diapositive58.PNG)
![](ppt/Diapositive59.PNG)
![](ppt/Diapositive60.PNG)
![](ppt/Diapositive61.PNG)
![](ppt/Diapositive62.PNG)
![](ppt/Diapositive63.PNG)
![](ppt/Diapositive64.PNG)
![](ppt/Diapositive65.PNG)
![](ppt/Diapositive66.PNG)
![](ppt/Diapositive67.PNG)
![](ppt/Diapositive68.PNG)
![](ppt/Diapositive69.PNG)
![](ppt/Diapositive70.PNG)
![](ppt/Diapositive71.PNG)
![](ppt/Diapositive72.PNG)
![](ppt/Diapositive73.PNG)
![](ppt/Diapositive74.PNG)
![](ppt/Diapositive75.PNG)
![](ppt/Diapositive76.PNG)
![](ppt/Diapositive77.PNG)
![](ppt/Diapositive78.PNG)
![](ppt/Diapositive79.PNG)
![](ppt/Diapositive80.PNG)
![](ppt/Diapositive81.PNG)
![](ppt/Diapositive82.PNG)
![](ppt/Diapositive83.PNG)
![](ppt/Diapositive84.PNG)
![](ppt/Diapositive85.PNG)
![](ppt/Diapositive86.PNG)
![](ppt/Diapositive87.PNG)
![](ppt/Diapositive88.PNG)
![](ppt/Diapositive89.PNG)
![](ppt/Diapositive90.PNG)
![](ppt/Diapositive91.PNG)
![](ppt/Diapositive92.PNG)
![](ppt/Diapositive93.PNG)
![](ppt/Diapositive94.PNG)
![](ppt/Diapositive95.PNG)
![](ppt/Diapositive96.PNG)
![](ppt/Diapositive97.PNG)
![](ppt/Diapositive98.PNG)
![](ppt/Diapositive99.PNG)
![](ppt/Diapositive100.PNG)
![](ppt/Diapositive101.PNG)
![](ppt/Diapositive102.PNG)
![](ppt/Diapositive103.PNG)
![](ppt/Diapositive104.PNG)
![](ppt/Diapositive105.PNG)
![](ppt/Diapositive106.PNG)
![](ppt/Diapositive107.PNG)
![](ppt/Diapositive108.PNG)
![](ppt/Diapositive109.PNG)
![](ppt/Diapositive110.PNG)
![](ppt/Diapositive111.PNG)
![](ppt/Diapositive112.PNG)
![](ppt/Diapositive113.PNG)
![](ppt/Diapositive114.PNG)
![](ppt/Diapositive115.PNG)
![](ppt/Diapositive116.PNG)
![](ppt/Diapositive117.PNG)
![](ppt/Diapositive118.PNG)
![](ppt/Diapositive119.PNG)
![](ppt/Diapositive120.PNG)
![](ppt/Diapositive121.PNG)
![](ppt/Diapositive122.PNG)
![](ppt/Diapositive123.PNG)
![](ppt/Diapositive124.PNG)
![](ppt/Diapositive125.PNG)
![](ppt/Diapositive126.PNG)
![](ppt/Diapositive127.PNG)
![](ppt/Diapositive128.PNG)
![](ppt/Diapositive129.PNG)
![](ppt/Diapositive130.PNG)
![](ppt/Diapositive131.PNG)
![](ppt/Diapositive132.PNG)
![](ppt/Diapositive133.PNG)
![](ppt/Diapositive134.PNG)
![](ppt/Diapositive135.PNG)
![](ppt/Diapositive136.PNG)
![](ppt/Diapositive137.PNG)
![](ppt/Diapositive138.PNG)
![](ppt/Diapositive139.PNG)
![](ppt/Diapositive140.PNG)
![](ppt/Diapositive141.PNG)
![](ppt/Diapositive142.PNG)
![](ppt/Diapositive143.PNG)
![](ppt/Diapositive144.PNG)
![](ppt/Diapositive145.PNG)
![](ppt/Diapositive146.PNG)
![](ppt/Diapositive147.PNG)
![](ppt/Diapositive148.PNG)
![](ppt/Diapositive149.PNG)
![](ppt/Diapositive150.PNG)
![](ppt/Diapositive151.PNG)
![](ppt/Diapositive152.PNG)
![](ppt/Diapositive153.PNG)
![](ppt/Diapositive154.PNG)
![](ppt/Diapositive155.PNG)
![](ppt/Diapositive156.PNG)
![](ppt/Diapositive157.PNG)
![](ppt/Diapositive158.PNG)
![](ppt/Diapositive159.PNG)
![](ppt/Diapositive160.PNG)
![](ppt/Diapositive161.PNG)
![](ppt/Diapositive162.PNG)
![](ppt/Diapositive163.PNG)
![](ppt/Diapositive164.PNG)
![](ppt/Diapositive165.PNG)
![](ppt/Diapositive166.PNG)
![](ppt/Diapositive167.PNG)
![](ppt/Diapositive168.PNG)
![](ppt/Diapositive169.PNG)
![](ppt/Diapositive170.PNG)
![](ppt/Diapositive171.PNG)
![](ppt/Diapositive172.PNG)
![](ppt/Diapositive173.PNG)
![](ppt/Diapositive174.PNG)
![](ppt/Diapositive175.PNG)
![](ppt/Diapositive176.PNG)
![](ppt/Diapositive177.PNG)
![](ppt/Diapositive178.PNG)
![](ppt/Diapositive179.PNG)
![](ppt/Diapositive180.PNG)
![](ppt/Diapositive181.PNG)
![](ppt/Diapositive182.PNG)
![](ppt/Diapositive183.PNG)
![](ppt/Diapositive184.PNG)
![](ppt/Diapositive185.PNG)
![](ppt/Diapositive186.PNG)
![](ppt/Diapositive187.PNG)
