Deep neural networks for detection of COVID-19, pneumonia and healthy individuals. For more information please read the article: http://link.springer.com/article/10.1007/s42600-021-00132-9

Abstract:

Purpose: We present image classifiers based on Dense Convolutional Networks and transfer learning to classify chest X-ray images according to three labels: COVID-19, pneumonia and normal.
Methods: We fine-tuned neural networks pretrained on ImageNet and applied a twice transfer learning approach, using NIH ChestX-ray14 dataset as an intermediate step. We also suggested a novelty called output neuron keeping, which changes the twice transfer learning technique. In order to clarify the modus operandi of the models, we used Layer-wise Relevance Propagation (LRP) to generate heatmaps.
Results: We were able to reach test accuracy of 100% on our test dataset. Twice transfer learning and output neuron keeping showed promising results improving performances, mainly in the beginning of the training process. Although LRP revealed that words on the X-rays can influence the networks' predictions, we discovered this had only a very small effect on accuracy.
Conclusion: Although clinical studies and larger datasets are still needed to further ensure good generalization, the state-of-the-art performances we achieved show that, with the help of artificial intelligence, chest X-rays can become a cheap and accurate auxiliary method for COVID-19 diagnosis. Heatmaps generated by LRP improve the interpretability of the deep neural networks and indicate an analytical path for future research on diagnosis. Twice transfer learning with output neuron keeping improved performances.

Citation:

Bassi, P.R.A.S., Attux, R. A deep convolutional neural network for COVID-19 detection using chest X-rays. Res. Biomed. Eng. (2021). https://doi.org/10.1007/s42600-021-00132-9
