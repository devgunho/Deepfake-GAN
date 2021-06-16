# Deepfake (GAN)

> https://github.com/iliasprc/Deep-Fakes/blob/master/README.md

A list of Deepfakes resources, deepfakes datasets, deepfake generation and detection methods

<br/>

## Table of Contents

- Datasets
- Deepfake Detection Methods
- Deepfake Generation Methods

<br/>

### Datasets

| Database                                                     | Real content   | Fake content                        |
| ------------------------------------------------------------ | -------------- | ----------------------------------- |
| [Flickr-Faces-HQ Dataset](https://github.com/NVlabs/ffhq-dataset) |                |                                     |
| [100K-Generated-Images](https://arxiv.org/pdf/1812.04948.pdf) |                | 100,000                             |
| [100K-Faces (2019)](https://generated.photos/)               |                | 100,000                             |
| [DFFD](https://arxiv.org/pdf/1910.01717.pdf)                 |                | 100,000 (StyleGAN) 200,000 (ProGAN) |
| [FSRemovalDB](https://arxiv.org/pdf/1911.05351.pdf)          |                | 150,000                             |
| [UADFV](https://arxiv.org/pdf/1806.02877.pdf)                | 49 (Youtube)   | 49 (FakeApp)                        |
| [DeepfakeTIMIT](https://arxiv.org/pdf/1812.08685.pdf)        |                | 620 (faceswap-GAN)                  |
| [FaceForensics++](https://github.com/ondyari/FaceForensics)  | 1000 (Youtube) | 1000 (FaceSwap) 1000 (DeepFake)     |
| [DeepFakeDetection](https://ai.googleblog.com/2019/09/contributing-data-to-deepfake-detection.html) | 363 (Actors)   | 3068 (DeepFake)                     |
| [Celeb-DF](https://github.com/danmohaha/celeb-deepfakeforensics) | 408 (Youtube)  | 795 (DeepFake)                      |
| [DFDC Preview](https://deepfakedetectionchallenge.ai/)       | 1131 (Actors)  | 4119 (Unknown)                      |

<br/>

### Deepfake Detection Methods

| Method                                                       | Code                                                       | Year |
| ------------------------------------------------------------ | ---------------------------------------------------------- | ---- |
| Detecting Facial Retouching Using Supervised Deep Learning [pdf](https://www3.nd.edu/~kwb/Bharati_Singh_Vatsa_Bowyer_TIFS_2016.pdf) |                                                            | 2016 |
| Progressive Growing of GANs for Improved Quality, Stability, and Variation [pdf](https://arxiv.org/pdf/1710.10196.pdf) |                                                            | 2017 |
| Exploiting Visual Artifacts to Expose Deepfakes and Face Manipulations | https://github.com/FalkoMatern/Exploiting-Visual-Artifacts | 2017 |
| Detecting Both Machine and Human Created Fake FaceImages In the Wild [pdf](https://dl.acm.org/doi/pdf/10.1145/3267357.3267367) |                                                            | 2017 |
| A Style-Based Generator Architecture for Generative Adversarial Networks [pdf](https://arxiv.org/pdf/1812.04948.pdf) | https://github.com/NVlabs/stylegan                         | 2018 |
| MesoNet: a Compact Facial Video Forgery Detection Network [pdf](https://arxiv.org/pdf/1809.00888.pdf) | https://github.com/DariusAf/MesoNet                        | 2018 |
| Detecting GAN-Generated Imagery Using Color Cues [pdf](https://arxiv.org/pdf/1812.08247.pdf) |                                                            | 2018 |
| Attributing Fake Images to GANs: Learning and Analyzing GAN Fingerprints [pdf](https://arxiv.org/pdf/1811.08180.pdf) |                                                            | 2018 |
| Speaker Inconsistency Detection in Tampered Video [pdf](https://publications.idiap.ch/downloads/papers/2018/Korshunov_EUSIPCO_2018.pdf) |                                                            | 2018 |
| Exposing Deep Fakes Using Inconsistent Head Poses [pdf](https://arxiv.org/pdf/1811.00661.pdf) |                                                            | 2018 |
| Two-Stream Neural Networks for Tampered Face Detection [pdf](https://arxiv.org/pdf/1803.11276.pdf) |                                                            | 2018 |
| Exposing DeepFake Videos By Detecting Face Warping Artifacts [pdf](https://arxiv.org/pdf/1811.00656.pdf) |                                                            | 2018 |
| Real or Fake? Spooﬁng State-Of-The-Art Face Synthesis Detection Systems [pdf](https://arxiv.org/pdf/1911.05351.pdf) | https://github.com/joaocneves/gan_fingerprint_removal      | 2019 |
| FakeSpotter: A Simple Baseline for Spotting AI-Synthesized Fake Faces [pdf](https://arxiv.org/pdf/1909.06122.pdf) |                                                            | 2019 |
| Detecting GAN generated Fake Images using Co-occurrence Matrices [pdf](https://arxiv.org/pdf/1903.06836.pdf) |                                                            | 2019 |
| Incremental Learning for the Detection and Classiﬁcation of GAN-Generated Images [pdf](https://arxiv.org/pdf/1910.01568.pdf) |                                                            | 2019 |
| Deepfake Video Detection Using Recurrent Neural Networks [pdf](https://engineering.purdue.edu/~dgueraco/content/deepfake.pdf) |                                                            | 2019 |
| Multi-task Learning For Detecting and Segmenting Manipulated Facial Images and Videos [pdf](https://arxiv.org/pdf/1906.06876.pdf) |                                                            | 2019 |
| Protecting World Leaders Against Deep Fakes [pdf](http://openaccess.thecvf.com/content_CVPRW_2019/papers/Media Forensics/Agarwal_Protecting_World_Leaders_Against_Deep_Fakes_CVPRW_2019_paper.pdf) |                                                            | 2019 |
| Recurrent Convolutional Strategies for Face Manipulation Detection in Videos [pdf](https://arxiv.org/pdf/1905.00582.pdf) |                                                            | 2019 |
| On Detecting GANs and Retouching based Synthetic Alterations [pdf](https://arxiv.org/pdf/1901.09237.pdf) |                                                            | 2019 |
| Detecting Photoshopped Faces by Scripting Photoshop [pdf](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Detecting_Photoshopped_Faces_by_Scripting_Photoshop_ICCV_2019_paper.pdf) | https://github.com/peterwang512/FALdetector                | 2019 |
| Detecting and Simulating Artifacts in GAN Fake Images [pdf](https://arxiv.org/pdf/1907.06515.pdf) | https://github.com/ColumbiaDVMM/AutoGAN                    | 2019 |
| Deepfake Video Detection through Optical Flow based CNN [pdf](http://openaccess.thecvf.com/content_ICCVW_2019/papers/HBU/Amerini_Deepfake_Video_Detection_through_Optical_Flow_Based_CNN_ICCVW_2019_paper.pdf) |                                                            | 2019 |
| Detecting Deep-Fake Videos from Appearance and Behavior [pdf](https://ieeexplore.ieee.org/abstract/document/9360904?casa_token=rzjFI2N2UjQAAAAA:t7pb30MdRz3-Sb8m2DMDleOL4VO6ti76QlHg513BBkr5ReTrk_xlUM6OVRHVUPc0RqtasslsTXcw) |                                                            | 2020 |
| Detecting Deep-Fake Videos from Phoneme-Viseme Mismatches [pdf](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w39/Agarwal_Detecting_Deep-Fake_Videos_From_Phoneme-Viseme_Mismatches_CVPRW_2020_paper.pdf) |                                                            | 2020 |
| Detecting Deepfakes with Metric Learning [pdf](https://ieeexplore.ieee.org/abstract/document/9107962?casa_token=J6JK_ok-0pAAAAAA:r5TFe9Uq3zq5EpD9PysfGsCA_4cbOhm4jjVCAmqKgL7e6v5YNn0hdgMQ-s7Lpd5cIi8XgVnB-zi9) |                                                            | 2020 |
| DeepVision: Deepfakes Detection Using Human Eye Blinking Pattern [pdf](https://ieeexplore.ieee.org/abstract/document/9072088) |                                                            | 2020 |

<br/>

### Deepfake Generation Methods

| Method                                                       | Code                                              |
| ------------------------------------------------------------ | ------------------------------------------------- |
| StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation [pdf](https://arxiv.org/pdf/1711.09020.pdf) | https://github.com/yunjey/stargan                 |
| Face2face: Real-Time Face Capture and Reenactment of RGB Videos[pdf](http://www.graphics.stanford.edu/~niessner/papers/2016/1facetoface/thies2016face.pdf) | https://github.com/datitran/face2face-demo        |
| A Style-Based Generator Architecture for Generative Adversarial Networks [pdf](https://arxiv.org/pdf/1812.04948.pdf) | https://github.com/NVlabs/stylegan                |
| STGAN: A Unified Selective Transfer Network for Arbitrary Image Attribute Editing [pdf](https://arxiv.org/pdf/1904.09709.pdf) | https://github.com/csmliu/STGAN                   |
| FaceSwap                                                     | https://github.com/MarekKowalski/FaceSwap         |
| FaceSwap GAN                                                 | https://github.com/shaoanlu/faceswap-GAN          |
| AttGAN: Facial Attribute Editing by Only Changing What You Want | https://github.com/LynnHo/AttGAN-Tensorflow       |
| Invertible Conditional GANs for image editing [pdf](https://arxiv.org/pdf/1611.06355.pdf) | https://github.com/Guim3/IcGAN                    |
| Fader Networks: Manipulating Images by Sliding Attributes [pdf](https://arxiv.org/pdf/1706.00409.pdf) | https://github.com/facebookresearch/FaderNetworks |

- [FaceApp](https://www.faceapp.com/)

- [Kaggle Deepfake Detection challenge](https://www.kaggle.com/c/deepfake-detection-challenge)

- [Xpression app : Your facial expression on anyone's face](https://xpression.jp/)

<br/>

