# Guided Image-to-Image Translation papers
- [Class Label Guided](#Class-Label-Guided)
- [Facial Landmark Guided](#Facial-Landmark-Guided)
- [Human Skeleton Guided](#Human-Skeleton-Guided)
- [Segmentation Map Guided](#Segmentation-Map-Guided)
- [Texture Patch Guided](#Texture-Patch-Guided)
- [Example Guided](#Example-Guided)
- [Attention Guided](#Attention-Guided)
- [Mask Guided](#Mask-Guided)
- [Text Guided](#Text-Guided)


## Class Label Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
AGUIT                | Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning |            | [1904.12428](https://arxiv.org/abs/1904.12428)         | [imlixinyang/AGUIT](https://github.com/imlixinyang/AGUIT) |
IcGAN                        | Invertible Conditional GANs for image editing                | NeurIPSW 2016                    | [1611.06355](https://arxiv.org/abs/1611.06355) | [Guim3/IcGAN](https://github.com/Guim3/IcGAN)                |
Conditional CycleGAN         | Conditional CycleGAN for Attribute Guided Face Image Generation | ECCV 2018                     | [1705.09966](https://arxiv.org/abs/1705.09966) |                                                              |
StarGAN                      | StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018                     | [1711.09020](https://arxiv.org/abs/1711.09020) | [yunjey/StarGAN](https://github.com/yunjey/StarGAN)          |
AttGAN                       | AttGAN: Facial Attribute Editing by Only Changing What You Want | TIP 2019                      | [1711.10678](https://arxiv.org/abs/1711.10678) | [LynnHo/AttGAN-Tensorflow](https://github.com/LynnHo/AttGAN-Tensorflow) |
SGGAN                       | Sparsely Grouped Multi-task Generative Adversarial Networks for Facial Attribute Manipulation | MM 2018                       | [1805.07509](https://arxiv.org/abs/1805.07509) | [zhangqianhui/Sparsely-Grouped-GAN](https://github.com/zhangqianhui/Sparsely-Grouped-GAN) |
GANimation                   | GANimation: Anatomically-aware Facial Animation from a Single Image | ECCV 2018 | [1807.09251](https://arxiv.org/abs/1807.09251) | [albertpumarola/GANimation](https://github.com/albertpumarola/GANimation) |
RelGAN                       | RelGAN: Multi-Domain Image-to-Image Translation via Relative Attributes | ICCV 2019                     | [1908.07269](https://arxiv.org/abs/1908.07269) | [elvisyjlin/RelGAN-PyTorch](https://github.com/elvisyjlin/RelGAN-PyTorch), [willylulu/RelGAN](https://github.com/willylulu/RelGAN) |

## Facial Landmark Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
G2GAN                                    | Geometry Guided Adversarial Facial Expression Synthesis      | MM 2018    | [1712.03474](https://arxiv.org/abs/1712.03474) |  
CMM-Net | Every Smile is Unique: Landmark-Guided Diverse Smile Generation | CVPR 2018 | [1802.01873](https://arxiv.org/abs/1802.01873) | |
C2GAN | Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation | MM 2019 | [1908.00999](https://arxiv.org/abs/1908.00999) | [Ha0Tang/C2GAN](https://github.com/Ha0Tang/C2GAN)  |

## Human Skeleton Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
GestureGAN | GestureGAN for Hand Gesture-to-Gesture Translation in the Wild | MM 2018 | [1808.04859](https://arxiv.org/abs/1808.04859) | [Ha0Tang/GestureGAN](https://github.com/Ha0Tang/GestureGAN) |
Pix2pixHD + Temporal Smoothing + FaceGAN | Everybody Dance Now                                          | ICCV 2019 | [1808.07371](https://arxiv.org/abs/1808.07371) | [project page](https://carolineec.github.io/everybody_dance_now/) |

## Segmentation Map Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
Pix2PixHD                                | High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs | CVPR 2018  | [1711.11585](https://arxiv.org/abs/1711.11585) | [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD)      |
Vid2Vid                                   | Video-to-Video Synthesis                                     | NeurIPS 2018  | [1808.06601](https://arxiv.org/abs/1808.06601) | [NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)          |
SPADE | Semantic Image Synthesis with Spatially-Adaptive Normalization | CVPR 2019 | [1903.07291](https://arxiv.org/abs/1903.07291) | [NVlabs/SPADE](https://github.com/NVlabs/SPADE) |
SelectionGAN | Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation | CVPR 2019 | [1904.06807](https://arxiv.org/abs/1904.06807) | [Ha0Tang/SelectionGAN](https://github.com/Ha0Tang/SelectionGAN) |
Art2Real     | Art2Real: Unfolding the Reality of Artworks via Semantically-Aware Image-to-Image Translation | CVPR 2019  | [1811.10666](https://arxiv.org/abs/1811.10666)               | [aimagelab/art2real](https://github.com/aimagelab/art2real) |
Few-shot vid2vid | Few-shot Video-to-Video Synthesis | NeurIPS 2019 | [1910.12713](https://arxiv.org/abs/1910.12713) | [NVlabs/few-shot-vid2vid](https://github.com/NVlabs/few-shot-vid2vid) |

## Texture Patch Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
TextureGAN                                | TextureGAN: Controlling Deep Image Synthesis with Texture Patches | CVPR 2018  | [1706.02823](https://arxiv.org/abs/1706.02823) | [janesjanes/Pytorch-TextureGAN](https://github.com/janesjanes/Pytorch-TextureGAN) |

## Example Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
EG-UNIT                      | Exemplar Guided Unsupervised Image-to-Image Translation      | ICLR 2019  | [1805.11145](https://arxiv.org/abs/1805.11145)               |    
## Attention Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
DA-GAN               | DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks | CVPR 2018  | [1802.06454](https://arxiv.org/abs/1802.06454) 
Attention-GAN        | Attention-GAN for Object Transfiguration in Wild Images      | ECCV 2018  | [1803.06798](https://arxiv.org/abs/1803.06798)         |   
Attention guided GAN | Unsupervised Attention-guided Image to Image Translation     | NeurIPS 2018  | [1806.02311](https://arxiv.org/abs/1806.02311)         | [AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation) |
|                      | Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention |            | [1806.06195](https://arxiv.org/abs/1806.06195)         |    
AttentionGAN         | Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation | IJCNN 2019 | [1903.12296](https://arxiv.org/abs/1903.12296)         | [Ha0Tang/AttentionGAN](https://github.com/Ha0Tang/AttentionGAN) |
U-GAT-IT             | U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation |  ICLR 2020  | [1907.10830](https://arxiv.org/abs/1907.10830)         | [taki0112/UGATIT](https://github.com/taki0112/UGATIT), [znxlwm/UGATIT-pytorch](https://github.com/znxlwm/UGATIT-pytorch) |

## Mask Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
ContrastGAN          | Generative Semantic Manipulation with Mask-Contrasting GAN   | ECCV 2018  | [1708.00315](https://arxiv.org/abs/1708.00315)         |               |
InstaGAN             | Instance-aware image-to-image translation                    | ICLR 2019  | [openreview](https://openreview.net/pdf?id=ryxwJhC9YX) | [sangwoomo/instagan](https://github.com/sangwoomo/instagan)  |
INIT                 | Towards Instance-level Image-to-Image Translation            | CVPR 2019  | [1905.01744](https://arxiv.org/abs/1905.01744)         | [project](http://zhiqiangshen.com/projects/INIT/index.html)  |
|                      | Mask-Guided Portrait Editing with Conditional GANs           | CVPR 2019  | [1905.10346](https://arxiv.org/abs/1905.10346)         | [cientgu/Mask_Guided_Portrait_Editing](https://github.com/cientgu/Mask_Guided_Portrait_Editing) |

## Text Guided
Model                                     | Paper                                                        | Conference | paper link                                     | code link                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
ControlGAN                                | Controllable Text-to-Image Generation                         | NeurIPS 2019 | [1909.07083](https://arxiv.org/abs/1909.07083) | [mrlibw/ControlGAN](https://github.com/mrlibw/ControlGAN) |
ManiGAN                                | ManiGAN: Text-Guided Image Manipulation                         |  | [1912.06203](https://arxiv.org/abs/1912.06203) | |

## Contributions
Feel free to send a PR or issue.
