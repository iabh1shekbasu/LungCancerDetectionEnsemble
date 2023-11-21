# Lung Cancer Detection from Thoracic CT Scans using an Ensemble of Deep Learning Models

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/iabh1shekbasu/LungCancerDetectionEnsemble/blob/main/Probability_Extraction_and_Analysis.ipynb)
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/lung-cancer-detection-from-thoracic-ct-scans/lung-nodule-classification-on-lidc-idri)](https://paperswithcode.com/sota/lung-nodule-classification-on-lidc-idri?p=lung-cancer-detection-from-thoracic-ct-scans)
[![Publication Month](https://img.shields.io/badge/Published-Nov%202023-blue)](https://springer.com/journal/521)
[![Journal](https://img.shields.io/badge/Journal-Neural%20Computing%20and%20Applications-brightgreen)](https://springer.com/journal/521)


#### [Nandita Gautam](https://www.linkedin.com/in/nandita-gautam-a7932b95/)\*, [Abhishek Basu](https://www.linkedin.com/in/iabhishekbasu/)\*, and [Ram Sarkar](http://www.jaduniv.edu.in/profile.php?uid=686)
\* Equally contributing first authors

Published in Neural Computing and Applications (Nov 2023), Springer

[Link to Paper](https://doi.org/10.1007/s00521-023-09130-7)

## Abstract
Lung cancer remains a prevalent and deadly disease, claiming numerous lives annually. Early detection plays a pivotal role in significantly improving survival rates, by up to 50–70%. Therefore, developing a robust lung cancer detection system holds immense potential to positively impact human survival. Computed tomography (CT) scan images offer invaluable information about lung nodules, and the emergence of machine learning and deep learning techniques has empowered radiologists in their diagnostic tasks. In this study, we propose a new ensemble of deep learning models to accurately classify the severity of lung nodules. Our approach leverages deep transfer learning and adopts an ensemble learning approach. Specifically, three state-of-the-art convolutional neural networks (CNN) models, namely ResNet-152, DenseNet-169, and EfficientNet-B7, are employed. To enhance the ensemble method's performance, we introduce a novel scheme for selecting and assigning weights to each base model. Unlike conventional methods that often rely on manual experimentation to set weights, our approach fuses the scores of two standard assessment metrics, ROC-AUC score, and F1-score, for a more accurate weight vector determination. To evaluate the effectiveness of our method, we conduct extensive testing using the publicly available CT scan dataset, LIDC-IDRI. Our proposed ensemble achieves an accuracy of 97.23%, surpassing various recent methods and outperforming commonly used ensemble techniques. Furthermore, our novel weight optimization strategy significantly reduces false negatives, leading to a sensitivity of 98.6%. .

## Contribution
1. A weighted average ensemble technique is proposed for boosting the performance of the base CNN models in lung cancer classification using CT scan images.
2. The weights assigned to the classifiers are determined by fusing two evaluation metrics - F1-score and ROC-AUC score. Instead of setting the weights based solely on the accuracy of classifiers or according to the results of experiments, we have used a hyperbolic tangent function, and weights are then optimized using a novel technique using the recall score of the base models.
3. The proposed model has been evaluated on the publicly available lung CT dataset, called the LIDC-IDRI dataset. The obtained results are found to be superior to those from state-of-the-art techniques, demonstrating the method’s applicability in the real world.

## Citation
If you're using this article or code in your research or applications, please consider citing using this BibTeX:

```bibtex
@article{Gautam2023,
  title={Lung cancer detection from thoracic CT scans using an ensemble of deep learning models},
  author={Gautam, Nandita and Basu, Abhishek and Sarkar, Ram},
  journal={Neural Computing and Applications},
  volume={},
  number={},
  pages={},
  year={2023},
  publisher={Springer},
  doi={10.1007/s00521-023-09130-7},
  url={https://doi.org/10.1007/s00521-023-09130-7},
}


```
