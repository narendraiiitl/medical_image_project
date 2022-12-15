# Medical-Image-Captioning-on-Chest-X-rays
Medical imaging is the process of creating visual representations of the interior of a body for clinical analysis as well as visual representation of the function of some organs or tissues. They are widely used in hospitals and clinics to determine fractures and diseases. The medical images are read and interpreted by specialized medical professionals and their findings regarding each body of area examined are communicated via written Medical Reports. The process of writing medical reports usually takes around 5–10 minutes per report. In a day the doctors have to write medical reports that number in 100s which can take a lot of their time. The objective of this case study is to build a deep learning model that automatically write the impression part of medical report of chest X-rays and alleviate some of the burden of the medical professional. Here I will be taking a publicly available dataset from Indiana University which consists of chest X-ray images and reports (in XML format) which contain information regarding the findings and impression of the X-ray. The goal is to predict the impressions of the medical report attached to the images.



# Results
| Sl No. | Model | BLEU-1 | BLEU-2 | BLEU-3 | BLEU-4
| - | --------------------- | ----------- | -- | -- | -- |
| 1. | Simple Encoder Decoder (greedy search) | 0.317412 |	0.308454 |	0.333496 |	0.366244 |

