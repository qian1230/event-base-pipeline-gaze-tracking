# event-base-pipeline-gaze-tracking
请自行下载shape_predictor_68_face_landmarks.dat
本代码为结合事件的非端到端特征提取高频远程注视追踪研究
注视追踪是预估人眼注视方向的过程，可广泛应用于认知科学、人机交互、教育和培训等领域。然而，基于图像的远程注视追踪方法存在准确性不足以及难以精准定位的问题。针对上述问题，本研究提出了一种结合事件相机的高频远程注视追踪模型，旨在提升远程注视追踪技术的准确性和可解释性。本研究采用非端到端的回归学习方法，提取影响注视方向的多种特征，包括头部姿态、面部位置和虹膜运动。通过改进的卡尔曼滤波器和滑动窗口进行虹膜位置的实时追踪，进一步提高了注视跟踪的精度和鲁棒性。实验结果表明，模型能够以高更新率进行注视跟踪，并在250FPS的分辨率下实现3.88度的平均角度误差，表现出较强的性能、可解释性和泛化能力。本研究提出结合事件相机的高频远程注视追踪方法，通过帧-事件混合非端到端的回归方法，显著提高了远程注视追踪的可解释性，为教育、人机交互等领域的应用提供了新的技术支持。
应用的数据主要为 RGBE-GAZE 数据集 
![image](https://github.com/user-attachments/assets/6d64ba22-5189-48fd-abae-4d6465d7b35c)
