Electric load forecasting has always been a key component of power grids. Many countries
have opened up electricity markets and facilitated the participation of multiple agents, which create a
competitive environment and reduce costs to consumers. In the electricity market, multi-step short-term load
forecasting becomes increasingly significant for electricity market bidding and spot price calculation, but the
performances of traditional algorithms are not robust and unacceptable enough. In recent years, the rise of
deep learning gives us the opportunity to improve the accuracy of multi-step forecasting further. In this paper,
we propose a novel model multi-scale convolutional neural network with time-cognition (TCMS-CNN).
At First, a deep convolutional neural network model based on multi-scale convolutions (MS-CNN) extracts
different level features that are fused into our network. In addition, we design an innovative time coding
strategy called the periodic coding strengthening the ability of the sequential model for time cognition
effectively. At last, we integrate MS-CNN and periodic coding into the proposed TCMS-CNN model with
an end-to-end training and inference process. With ablation experiments, the MS-CNN and periodic coding
methods had better performances obviously than the most popular methods at present. Specifically, for
48-step point load forecasting, the TCMS-CNN had been improved by 34.73%, 14.22%, and 19.05% on
MAPE than the state-of-the-art methods recursive multi-step LSTM (RM-LSTM), direct multi-step MSCNN
(DM-MS-CNN), and the direct multi-step GCNN (DM-GCNN), respectively. For 48-step probabilistic
load forecasting, the TCMS-CNN had been improved by 3.54% and 6.77% on average pinball score than
the DM-MS-CNN and the DM-GCNN. These results show a great promising potential applied in practice.