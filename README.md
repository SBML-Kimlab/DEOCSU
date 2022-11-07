# DEOCSU
DEOCSU(**DE**ep-learning **O**ptimized **C**hIP-exo peak calling **SU**ite) is an deep-learning based ChIP-exo peak calling tool based on deep convolutional neural network model. The tool is named after the lab mascot pet DEOCSU[dəksu:] whose main staff is Seojoung Park in SBML-Kim lab.
#

![Figure1](https://user-images.githubusercontent.com/42198206/200239582-813f61a0-7c78-422d-aff1-5c42173199bb.png)

Chromatin immunoprecipitation (ChIP) has been widely used to investigate DNA-binding proteins (e.g. transcription factors (TF) or transcriptional machinery) and their binding location at the genome-scale level. Although ChIP-exo increases the signal-to-noise ratio and allows researchers to identify high-resolution binding sites, a peak calling step for selecting bona fide peaks is time-consuming, and labor-intensive which is a major rate-limiting step of ChIP-exo data analysis. 

- DEOCSU entails the deep convolutional neural network model which was trained with curated ChIP-exo peak data to distinguish the visualized data of bona fide peaks from false ones. 

- Performance validation of the trained deep-learning model indicated its high accuracy, high precision, and high recall of over 95%. 

- DEOCSU can be executed on a cloud computing platform or the local environment. 

- With visualization software(https://github.com/SBML-Kimlab/MetaScope), adjustable options such as the threshold of peak probability, and iterable updating of the pre-trained model, DEOCSU can be optimized for users’ specific needs.



