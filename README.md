#   <div align="center">  SMSProMyoT1 </div>
##  <div align="center"> Open-Source Myocardial T1 mapping accelerated with SMS: combining an auto-calibrated blip-bSSFP readout
% with VERSE-MB pulses

<div align="justify"> Quantitative MR methods require reproducibility studies to evaluate their accuracy and precision which can be difficult when MR sequences can vary between centers and scanners. In addition, faster prototyping for concept testing and improvement is challenging and time consuming.</div>

<br/>

This package offers an open-source Simultaneous-Slice Prototype of Myocardial T1 mapping (SMS-ProMyoT1) using Pulseq [[1,2]](#references) which includes an inversion recovery T1 mapping sequence with a triggering scheme. ProMyoT1 accessibility allows faster implementation of new ideas, while its applicability to different vendors though Pulseq versatility makes it an easier route for reproducibility studies. 



<br/>

If you use the sequence ProMyoT1 in your work, cite as:

```
Andreia S Gaspar, Nuno A Silva, Rita G Nunes. Open-Source Myocardial T1 mapping accelerated with SMS: combining an auto-calibrated blip-bSSFP readout with VERSE-MB pulses” Proc. of Annual Meeting ISMRM 2022, London, 2022.
```

## Packages
SMS-ProMyoT1 can be build with Matlab: 
*  **SMS-ProMyoT1**: 
	* **SMS-ProMyoT1_af1**  can be build from code in SMS-ProMyoT1_af1 folder. Files in VERSE_RFpulse, bSSFP_readout and bSSFP_ACS folder should be added. 
	* **SMS-ProMyoT1_af2**  can be build from code in SMS-ProMyoT1_af2 folder. Files in VERSE_RFpulse,bSSFP_readout, bSSFP_ACS and FLASH_ACS folder should be added. 


## Requirements
In order to create a `SMS-ProMyoT1.seq` file you will need: 
*  **PULSEQ**:  **Pulseq** package available at: https://github.com/pulseq/pulseq or for python: https://github.com/imr-framework/pypulseq 
*   **VERSE Optimization**:  
	* **VERSE** [[3]](#references)  package available at: https://github.com/mriphysics/verse-mb



## References
1. Layton KJ, Kroboth S, Jia F, Littin S, Yu H, Leupold J, Nielsen JF, Stöcker T and Zaitsev M. Pulseq: A rapid and hardware‐independent pulse sequence prototyping framework. Magn Reson Med. 2017;77:1544-1552. https://doi.org/10.1002/mrm.26235
2. Keerthi R, Geethanath S, and Vaughan J. PyPulseq: A Python Package for MRI Pulse Sequence Design. Journal of Open Source Software. 2019;4(42): 1725. https://doi.org/10.21105/joss.01725
3. Abo Seada S, Price AN, Schneider T, Hajnal JV, Malik SJ. Multiband RF pulse design for realistic gradient performance. Magn Reson Med. 2019;81(1):362-376.