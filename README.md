# Automated Diagnosis of Lung Cancer Through Convolutional Neural Networks: A Deep Learning Approach

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Diagnosis-of-Lung-Cancer---CNN/6cd67aac2e28acf969673fd34181d386742fa14e/Figures/IconLung.svg">
</p>

Abstract— Cancer is the second most common cause of death in the world, where lung disease is outlined as the leading cause of death from cancer. This problem is approached from different perspectives, and the computerized tomography is one of the best tools for early diagnosis of this disease. Therefore, this article proposes a new diagnostic support system based on these images. The system is made up of three main stages and each one of them is implemented under the new deep learning techniques. Initially, candidate nodules are segmented through the MultiResUNet 3D convolutional neural network. Later, the segmentations are used to train a second CNN and eliminate false positives. Finally, a third CNN is trained to classify nodules according to their character (malignant or benign). The system was validated in its three stages and it was found that: the segmentation achieved an accuracy above 99%. The elimination of false positives and the classification of nodules reached average accuracies above 89% and 81% respectively, and even, the latter reached an accuracy above 87%, surpassing most developments applied so far.

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Diagnosis-of-Lung-Cancer---CNN/b9a24e185fd348ff103dee77461c52d3edfa1606/Figures/Figure%202.svg">
</p>

The methodology of the proposed system was divided into three main stages. In the first one, the computed axial tomography of 1010 subjects was used to segment the nodules present inside the thoracic region. The process was carried out with the convolutional neural network MultiResUNet. Second, the elimination of false positives generated in the segmentation was carried out. Finally, the segmented nodules were used to train a binary CNN for classification according to their pathological character. That is, if these are potentially malignant or benign nodules. The following figure shows a general diagram of the elements that make up the diagnostic assistant.

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Diagnosis-of-Lung-Cancer---CNN/f4fa72c5f6c8b58452a6257e3bfb990e0bb44d32/Figures/Figure%205.svg">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Qsinap/Diagnosis-of-Lung-Cancer---CNN/601be672ebb43c533e3982f61cfed99daa4b553a/Figures/Figure%207a.svg">
</p>

This research was supported by the research division from [INDIGO Technologies.](https://indigo.tech/)

