# AI-design-contest-QCNN-KWS-processor
Our Intention is to work on KWS processor which inculdes a Mel-Frequency Cepstrum Coefficients (MFCC) feature extractor and a quantized Convolutional Neural Network (QCNN) accelerator for low-power KWS. The keyword spotting (KWS) system is one of the most important interfaces between humans and machines since it is usually the start of automatic speech recognition and natural language processing techniques. 

Reference design QCNN accelerator is implemented and verified under TSMC 22nm ULL technology, with the area of 1.42mm2, and it was found that the QCNN accelerator can achieve 5.26µW/9.08µW power consumption in 4bit/8bit work mode with accuracy of 88% and 93% respectively. (Link to paper is given below) 

Reference: 'https://doi.org/10.1109/ACCESS.2020.3037931' and 'https://doi.org/10.1109/ACCESS.2019.2960948'

We propose to utilize generative AI to design QCNN accelerator with low power KWS in Caravel SoC environment. 
