# Diagnosis-of-Lung-Cancer---CNN
Automated Diagnosis of Lung Cancer Through Convolutional Neural Networks: A Deep Learning Approach

Abstract— Cancer is the second most common cause of death in the world, where lung disease is outlined as the leading cause of death from cancer. This problem is approached from different perspectives, and the computerized tomography is one of the best tools for early diagnosis of this disease. Therefore, this article proposes a new diagnostic support system based on these images. The system is made up of three main stages and each one of them is implemented under the new deep learning techniques. Initially, candidate nodules are segmented through the MultiResUNet 3D convolutional neural network. Later, the segmentations are used to train a second CNN and eliminate false positives. Finally, a third CNN is trained to classify nodules according to their character (malignant or benign). The system was validated in its three stages and it was found that: the segmentation achieved an accuracy above 99%. The elimination of false positives and the classification of nodules reached average accuracies above 89% and 81% respectively, and even, the latter reached an accuracy above 87%, surpassing most developments applied so far
