# Quantization papers
> Last update: 2022.01.05

## Survey
### **# 000**
- **(arXiv 2018)** A Survey on Methods and Theories of Quantized Neural Networks [[Paper](https://arxiv.org/abs/1808.04752)]
- **(arXiv 2021)** A White Paper on Neural Network Quantization [[Paper](https://arxiv.org/abs/2106.08295)]
- **(arXiv 2021)** A Survey of Quantization Methods for Efficient Neural Network Inference [[Paper](https://arxiv.org/abs/2103.13630)]
- Paper archive [[Github page](https://github.com/htqin/awesome-model-quantization)]

## Quantization-aware training
### **# 001**
- **(ECCV 2016)** XNOR-Net: ImageNet Classification Using Binary Convolutional Neural Networks [[Paper](https://arxiv.org/abs/1603.05279)]
- **(arXiv 2016)** Ternary Weight Networks [[Paper](https://arxiv.org/abs/1605.04711)]
- **(arXiv 2016)** DoReFa-Net: Training Low Bitwidth Convolutional Neural Networks with Low Bitwidth Gradients [[Paper](https://arxiv.org/abs/1606.06160)]
- **(CVPR 2017)** Deep Learning with Low Precision by Half-wave Gaussian Quantization [[Paper](https://arxiv.org/abs/1702.00953)]

## Designing quantizers
### **# 002**
- **(arXiv 2018)** PACT: Parameterized Clipping Activation for Quantized Neural Networks [[Paper](https://arxiv.org/abs/1805.06085)]
- **(ECCV 2018)** LQ-Nets: Learned Quantization for Highly Accurate and Compact Deep Neural Networks [[Paper](https://arxiv.org/abs/1807.10029)]
- **(CVPR 2019)** Learning to Quantize Deep Networks by Optimizing Quantization Intervals With Task Loss [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Jung_Learning_to_Quantize_Deep_Networks_by_Optimizing_Quantization_Intervals_With_CVPR_2019_paper.html)]
- **(CVPR 2021)** Learnable Companding Quantization for Accurate Low-bit Neural Networks [[Paper](https://arxiv.org/abs/2103.07156)]

## Training techniques/heuristics
### **# 003**
- **(ICLR 2017)** Incremental Network Quantization: Towards Lossless CNNs with Low-Precision Weights [[Paper](https://arxiv.org/abs/1702.03044)]
- **(CVPR 2018)** Towards Effective Low-bitwidth Convolutional Neural Networks [[Paper](https://arxiv.org/abs/1711.00205)]
- **(arXiv 2019)** QKD: Quantization-aware Knowledge Distillation [[Paper](https://arxiv.org/abs/1911.12491)]
- **(CVPR 2020)** Training Quantized Neural Networks with a Full-precision Auxiliary Module [[Paper](https://arxiv.org/abs/1903.11236)]
- **(ECCV 2020)** PROFIT: A Novel Training Method for sub-4-bit MobileNet Models [[Paper](https://arxiv.org/abs/2008.04693)]

## Adaptive quantization
### **# 004**
- **(CVPR 2020)** AdaBits: Neural Network Quantization with Adaptive Bit-Widths [[Paper](https://arxiv.org/abs/1912.09666)]
- **(arXiv 2020)** Switchable Precision Neural Networks [[Paper](https://arxiv.org/abs/2002.02815)]
- **(ICCV 2021)** Bit-Mixer: Mixed-precision networks with runtime bit-width selection [[Paper](https://arxiv.org/abs/2103.17267)]

## Overcoming non-differentiability
### **# 005**
- **(CVPR 2019)** Quantization Networks [[Paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Yang_Quantization_Networks_CVPR_2019_paper.html)]
- **(ICCV 2019)** Differentiable Soft Quantization: Bridging Full-Precision and Low-Bit Neural Networks [[Paper](https://arxiv.org/abs/1908.05033)]
- **(ICLR 2019)** ProxQuant: Quantized Neural Networks via Proximal Operators [[Paper](https://openreview.net/forum?id=HyzMyhCcK7)]
- **(NeurIPS 2019)** MetaQuant: Learning to Quantize by Learning to Penetrate Non-differentiable Quantization [[Paper](https://papers.nips.cc/paper/2019/hash/f8e59f4b2fe7c5705bf878bbd494ccdf-Abstract.html)]
- **(CVPR 2021)** Network Quantization with Element-wise Gradient Scaling [[Project site](https://cvlab.yonsei.ac.kr/projects/EWGS/)]
- **(ICCV 2021)** Distance-aware Quantization [[Project site](https://cvlab.yonsei.ac.kr/projects/DAQ/)]

## Binary networks
### **# 006**
- **(NIPS 2015)** BinaryConnect- Training Deep Neural Networks with binary weights during propagations [[Paper](https://arxiv.org/abs/1511.00363)]
- **(ECCV 2018)** Bi-Real Net: Enhancing the Performance of 1-bit CNNs With Improved Representational Capability and Advanced Training Algorithm [[Paper](https://arxiv.org/abs/1808.00278)]
- **(CVPR 2020)** Forward and Backward Information Retention for Accurate Binary Neural Networks [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Qin_Forward_and_Backward_Information_Retention_for_Accurate_Binary_Neural_Networks_CVPR_2020_paper.pdf)]
- **(ICCV 2021)** ReCU- Reviving the Dead Weights in Binary Neural Networks [[Paper](https://arxiv.org/abs/2103.12369)]

## Mixed-precision
### **# 007**
- **(CVPR 2019)** HAQ- Hardware-Aware Automated Quantization [[Paper](https://arxiv.org/abs/1811.08886?)]
- **(ICCV 2019)** HAWQ: Hessian AWare Quantization of Neural Networks with Mixed-Precision [[Paper](https://arxiv.org/abs/1905.03696)]
- **(NIPS 2020)** HAWQ-V2: Hessian Aware trace-Weighted Quantization of Neural Networks [[Paper](https://arxiv.org/abs/1911.03852)]
- **(ICLR 2021)** BSQ: EXPLORING BIT-LEVEL SPARSITY FOR MIXEDPRECISION NEURAL NETWORK QUANTIZATION [[Paper](https://openreview.net/forum?id=TiXl51SCNw8)]

## Post-training quantization
### **# 008**
- **(ICCV 2019)** Data-Free Quantization Through Weight Equalization and Bias Correction [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.pdf)]
- **(CVPR 2020)** ZeroQ: A Novel Zero Shot Quantization Framework [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_ZeroQ_A_Novel_Zero_Shot_Quantization_Framework_CVPR_2020_paper.pdf)]
- **(ICML 2020)** Up or Down? Adaptive Rounding for Post-Training Quantization [[Paper](https://arxiv.org/abs/2004.10568)]
- **(ICCV 2020)** Low-bit Quantization of Neural Networks for Efficient Inference [[Paper](https://arxiv.org/abs/1902.06822)]
- **(ICLR 2021)** BRECQ: PUSHING THE LIMIT OF POST-TRAINING QUANTIZATION BY BLOCK RECONSTRUCTION [[Paper](https://openreview.net/forum?id=POWv6hDd9XH)]

## Zero-Shot quantization
### **# 009**
- **(ICCV 2019)** Data-Free Quantization Through Weight Equalization and Bias Correction [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Nagel_Data-Free_Quantization_Through_Weight_Equalization_and_Bias_Correction_ICCV_2019_paper.pdf)]
- **(CVPR 2020)** ZeroQ: A Novel Zero Shot Quantization Framework [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Cai_ZeroQ_A_Novel_Zero_Shot_Quantization_Framework_CVPR_2020_paper.pdf)]
- **(CVPR 2021)** Diversifying Sample Generation for Accurate Data-Free Quantization [[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Zhang_Diversifying_Sample_Generation_for_Accurate_Data-Free_Quantization_CVPR_2021_paper.pdf)]
- **(CVPR 2021)** Zero-shot Adversarial Quantization [[Paper](https://arxiv.org/abs/2103.15263)]

## Applications - Super-resolution task
### **# 010**
- **(ECCV 2020)** Binarized Neural Network for Single Image Super Resolution [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490086.pdf)]
- **(ECCV 2020)** PAMS: Quantized Super-Resolution via Parameterized Max Scale [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700562.pdf)]
- **(ACM MM 2021)** Fully Quantized Image Super-Resolution Networks [[Paper](https://arxiv.org/abs/2011.14265)]
- **(WACV 2022)** DAQ: Distribution-Aware Quantization for Deep Image Super-Resolution Networks [[Paper](https://arxiv.org/abs/2012.11230)]


## Designing network architectures
### **# 000**
- **()** ?? [[Paper]()]

## Fixed-point quantization
### **# 000**
- **()** ?? [[Paper]()]
