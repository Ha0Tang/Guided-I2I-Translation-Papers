# Guided Image-to-Image Translation papers

**Feel free to send a PR or issue. (constantly updating)**

- [Class Label Guided](#Class-Label-Guided)
- [Action Unit Guided](#Action-Unit-Guided)
- [Facial Landmark Guided](#Facial-Landmark-Guided)
- [Human Skeleton Guided](#Human-Skeleton-Guided)
- [Segmentation Map Guided](#Segmentation-Map-Guided)
- [Texture Patch Guided](#Texture-Patch-Guided)
- [Example Guided](#Example-Guided)
- [Attention Guided](#Attention-Guided)
- [Mask Guided](#Mask-Guided)
- [Text Guided](#Text-Guided)


## Class Label Guided
Model                                     | Paper                                                        | Conference | Arxiv                                      | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
IcGAN                        | Invertible Conditional GANs for image editing                | NeurIPSW 2016                    | [1611.06355](https://arxiv.org/abs/1611.06355) | [Guim3/IcGAN](https://github.com/Guim3/IcGAN)                |
Conditional CycleGAN         | Conditional CycleGAN for Attribute Guided Face Image Generation | ECCV 2018                     | [1705.09966](https://arxiv.org/abs/1705.09966) |                                                              |
StarGAN                      | StarGAN: Uniﬁed Generative Adversarial Networks for Multi-Domain Image-to-Image Translation | CVPR 2018                     | [1711.09020](https://arxiv.org/abs/1711.09020) | [yunjey/StarGAN](https://github.com/yunjey/StarGAN)          |
AGUIT                | Attribute Guided Unpaired Image-to-Image Translation with Semi-supervised Learning |            | [1904.12428](https://arxiv.org/abs/1904.12428)         | [imlixinyang/AGUIT](https://github.com/imlixinyang/AGUIT) |
AttGAN                       | AttGAN: Facial Attribute Editing by Only Changing What You Want | TIP 2019                      | [1711.10678](https://arxiv.org/abs/1711.10678) | [LynnHo/AttGAN-Tensorflow](https://github.com/LynnHo/AttGAN-Tensorflow) |
SGGAN                       | Sparsely Grouped Multi-task Generative Adversarial Networks for Facial Attribute Manipulation | MM 2018                       | [1805.07509](https://arxiv.org/abs/1805.07509) | [zhangqianhui/Sparsely-Grouped-GAN](https://github.com/zhangqianhui/Sparsely-Grouped-GAN) |
RelGAN                       | RelGAN: Multi-Domain Image-to-Image Translation via Relative Attributes | ICCV 2019                     | [1908.07269](https://arxiv.org/abs/1908.07269) | [elvisyjlin/RelGAN-PyTorch](https://github.com/elvisyjlin/RelGAN-PyTorch), [willylulu/RelGAN](https://github.com/willylulu/RelGAN) |

## Action Unit Guided
Model                                     | Paper                                                        | Conference | Arxiv                                      | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
GANimation                   | GANimation: Anatomically-aware Facial Animation from a Single Image | ECCV 2018 | [1807.09251](https://arxiv.org/abs/1807.09251) | [albertpumarola/GANimation](https://github.com/albertpumarola/GANimation) |

## Facial Landmark Guided
Model                                     | Paper                                                        | Conference | Arxiv                                      | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
G2GAN                                    | Geometry Guided Adversarial Facial Expression Synthesis      | MM 2018    | [1712.03474](https://arxiv.org/abs/1712.03474) |  
CMM-Net | Every Smile is Unique: Landmark-Guided Diverse Smile Generation | CVPR 2018 | [1802.01873](https://arxiv.org/abs/1802.01873) | |
C2GAN | Cycle In Cycle Generative Adversarial Networks for Keypoint-Guided Image Generation | MM 2019 | [1908.00999](https://arxiv.org/abs/1908.00999) | [Ha0Tang/C2GAN](https://github.com/Ha0Tang/C2GAN)  |
|       | Few-Shot Adversarial Learning of Realistic Neural Talking Head Models      | ICCV 2019 | [1905.08233](https://arxiv.org/abs/1905.08233) | [grey-eye/talking-heads](https://github.com/grey-eye/talking-heads) |

## Human Skeleton Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
PG2                                      | Pose Guided Person Image Generation                           | NeurIPS 2017 | [1705.09368](https://arxiv.org/abs/1705.09368) | [charliememory/Pose-Guided-Person-Image-Generation](https://github.com/charliememory/Pose-Guided-Person-Image-Generation)
PoseGAN  | Deformable GANs for Pose-Based Human Image Generation |  CVPR 2018 | [1801.00055](https://arxiv.org/abs/1801.00055) | [AliaksandrSiarohin/pose-gan](https://github.com/AliaksandrSiarohin/pose-gan)
VUnet | A Variational U-Net for Conditional Appearance and Shape Generation | CVPR 2018 | [1804.04694](https://arxiv.org/abs/1804.04694) | [CompVis/vunet](https://github.com/CompVis/vunet)
|                | Disentangled Person Image Generation | CVPR 2018  | [1712.02621](https://arxiv.org/abs/1712.02621) | [charliememory/Disentangled-Person-Image-Generation](https://github.com/charliememory/Disentangled-Person-Image-Generation) |
GestureGAN | GestureGAN for Hand Gesture-to-Gesture Translation in the Wild | MM 2018 | [1808.04859](https://arxiv.org/abs/1808.04859) | [Ha0Tang/GestureGAN](https://github.com/Ha0Tang/GestureGAN) |
Pose-Transfer | Progressive Pose Attention for Person Image Generation | CVPR 2019 | [1904.03349](https://arxiv.org/abs/1904.03349) | [tengteng95/Pose-Transfer](https://github.com/tengteng95/Pose-Transfer) |
TriangleGAN | Gesture-to-Gesture Translation in the Wild via Category-Independent Conditional Maps | MM 2019 | [1907.05916](https://arxiv.org/abs/1907.05916) | [yhlleo/TriangleGAN](https://github.com/yhlleo/TriangleGAN) |
Pix2pixHD + Temporal Smoothing + FaceGAN | Everybody Dance Now                                          | ICCV 2019 | [1808.07371](https://arxiv.org/abs/1808.07371) | [project page](https://carolineec.github.io/everybody_dance_now/) |

## Segmentation Map Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
Pix2PixHD                                | High-Resolution Image Synthesis and Semantic Manipulation with Conditional GANs | CVPR 2018  | [1711.11585](https://arxiv.org/abs/1711.11585) | [NVIDIA/pix2pixHD](https://github.com/NVIDIA/pix2pixHD)      |
Vid2Vid                                   | Video-to-Video Synthesis                                     | NeurIPS 2018  | [1808.06601](https://arxiv.org/abs/1808.06601) | [NVIDIA/vid2vid](https://github.com/NVIDIA/vid2vid)          |
SPADE | Semantic Image Synthesis with Spatially-Adaptive Normalization | CVPR 2019 | [1903.07291](https://arxiv.org/abs/1903.07291) | [NVlabs/SPADE](https://github.com/NVlabs/SPADE) |
SelectionGAN | Multi-Channel Attention Selection GAN with Cascaded Semantic Guidance for Cross-View Image Translation | CVPR 2019 | [1904.06807](https://arxiv.org/abs/1904.06807) | [Ha0Tang/SelectionGAN](https://github.com/Ha0Tang/SelectionGAN) |
Art2Real     | Art2Real: Unfolding the Reality of Artworks via Semantically-Aware Image-to-Image Translation | CVPR 2019  | [1811.10666](https://arxiv.org/abs/1811.10666)               | [aimagelab/art2real](https://github.com/aimagelab/art2real) |
|                      | Mask-Guided Portrait Editing with Conditional GANs           | CVPR 2019  | [1905.10346](https://arxiv.org/abs/1905.10346)         | [cientgu/Mask_Guided_Portrait_Editing](https://github.com/cientgu/Mask_Guided_Portrait_Editing) |
Few-shot Vid2Vid | Few-shot Video-to-Video Synthesis | NeurIPS 2019 | [1910.12713](https://arxiv.org/abs/1910.12713) | [NVlabs/few-shot-vid2vid](https://github.com/NVlabs/few-shot-vid2vid) |

## Texture Patch Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
TextureGAN                                | TextureGAN: Controlling Deep Image Synthesis with Texture Patches | CVPR 2018  | [1706.02823](https://arxiv.org/abs/1706.02823) | [janesjanes/Pytorch-TextureGAN](https://github.com/janesjanes/Pytorch-TextureGAN) |
Guided-pix2pix                            | Guided Image-to-Image Translation with Bi-Directional Feature Transformation | ICCV 2019 | [1910.11328](https://arxiv.org/abs/1910.11328) | [vt-vl-lab/Guided-pix2pix](https://github.com/vt-vl-lab/Guided-pix2pix)

## Example Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
EG-UNIT                      | Exemplar Guided Unsupervised Image-to-Image Translation      | ICLR 2019  | [1805.11145](https://arxiv.org/abs/1805.11145)               |   [charliememory/EGSC-IT](https://github.com/charliememory/EGSC-IT) |
Pix2pixSC                                  | Example-Guided Style-Consistent Image Synthesis from Semantic Labeling | CVPR 2019 | [1906.01314](https://arxiv.org/abs/1906.01314) | [cxjyxxme/pix2pixSC](https://github.com/cxjyxxme/pix2pixSC)

## Attention Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
DA-GAN               | DA-GAN: Instance-level Image Translation by Deep Attention Generative Adversarial Networks | CVPR 2018  | [1802.06454](https://arxiv.org/abs/1802.06454) 
Attention-GAN        | Attention-GAN for Object Transfiguration in Wild Images      | ECCV 2018  | [1803.06798](https://arxiv.org/abs/1803.06798)         |   
UAIT | Unsupervised Attention-guided Image to Image Translation     | NeurIPS 2018  | [1806.02311](https://arxiv.org/abs/1806.02311)         | [AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation](https://github.com/AlamiMejjati/Unsupervised-Attention-guided-Image-to-Image-Translation) |
|                      | Show, Attend and Translate: Unsupervised Image Translation with Self-Regularization and Attention |  TIP 2019 | [1806.06195](https://arxiv.org/abs/1806.06195)         |    
AttentionGAN         | Attention-Guided Generative Adversarial Networks for Unsupervised Image-to-Image Translation | IJCNN 2019 | [1903.12296](https://arxiv.org/abs/1903.12296)         | [Ha0Tang/AttentionGAN](https://github.com/Ha0Tang/AttentionGAN) |
U-GAT-IT             | U-GAT-IT: Unsupervised Generative Attentional Networks with Adaptive Layer-Instance Normalization for Image-to-Image Translation |  ICLR 2020  | [1907.10830](https://arxiv.org/abs/1907.10830)         | [taki0112/UGATIT](https://github.com/taki0112/UGATIT), [znxlwm/UGATIT-pytorch](https://github.com/znxlwm/UGATIT-pytorch) |

## Mask Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
ContrastGAN          | Generative Semantic Manipulation with Mask-Contrasting GAN   | ECCV 2018  | [1708.00315](https://arxiv.org/abs/1708.00315)         |               |
InstaGAN             | Instance-aware image-to-image translation                    | ICLR 2019  | [1812.10889](https://arxiv.org/abs/1812.10889) | [sangwoomo/instagan](https://github.com/sangwoomo/instagan)  |
INIT                 | Towards Instance-level Image-to-Image Translation            | CVPR 2019  | [1905.01744](https://arxiv.org/abs/1905.01744)         | [project](http://zhiqiangshen.com/projects/INIT/index.html)  |

## Text Guided
Model                                     | Paper                                                        | Conference | Arxiv                                     | Code                                                    |
----------------------------------------- | ------------------------------------------------------------ | ---------- | ---------------------------------------------- | ------------------------------------------------------------ |
ControlGAN                                | Controllable Text-to-Image Generation                         | NeurIPS 2019 | [1909.07083](https://arxiv.org/abs/1909.07083) | [mrlibw/ControlGAN](https://github.com/mrlibw/ControlGAN) |
DMIT                                        | Multi-mapping Image-to-Image Translation via Learning Disentanglement | NeurIPS 2019 | [1909.07877](https://arxiv.org/abs/1909.07877) | [Xiaoming-Yu/DMIT](https://github.com/Xiaoming-Yu/DMIT) |
ManiGAN                                | ManiGAN: Text-Guided Image Manipulation                         |  | [1912.06203](https://arxiv.org/abs/1912.06203) | |
