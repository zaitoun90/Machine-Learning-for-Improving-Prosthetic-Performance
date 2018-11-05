# Machine-Learning-for-Improving-Prosthetic-Performance
Welcome to the Machine-Learning-for-Improving-Prosthetic-Performance wiki! # What is LPE? Myoelectric control has been extensively used for control of hand prostheses. The performance of this kind of control is however, relying on different practical factors. One of these factor is the Limb Positions Effect. Changes in the arm position during use will impact the muscles activity, length and shape. This in turn influences the quality of control. # What is the problem? the Limb Position Effect (LPE) is known to degrade the performance of a machine learning (ML) based myoelectric control. How are the researchs tried to solve this problem? researchers have used accelerometer (ACC) data besides Electromyography (EMG) for ML based control. So they can determined the specific class by using accelerometer data, More sensors used. How do we solve the problem? we show a different approach towards mitigating LPE. We hypothesize that the LPE introduces non-linearities in EMG and therefore, non-linear ML methods should be used to model EMG affected by LPE. This approach is different because, in the past, multimodal data (ACC+EMG) was used to improve the performance of linear ML- based methods (e.g. LDA), whereas, we propose to use non-linear models (e.g. SVM) to create a better model for the EMG affected by LPE.
