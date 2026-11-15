# Haisheng Fu

Postdoctoral researcher at the University of British Columbia, Vancouver, Canada

[Academic homepage](https://fengyurenpingsheng.github.io/) · [Google Scholar](https://scholar.google.com/citations?user=vGglk-EAAAAJ&hl=en) · [UBC TEA Group](https://tea.ece.ubc.ca/) · [Email](mailto:haisheng.fu@ubc.ca)

I began my PhD in Electronic Science and Technology at **Xi’an Jiaotong University** in 2018 with Feng Liang. My dissertation focused on end-to-end image compression with autoencoders. From 2021 to 2023, I did joint doctoral research at **Simon Fraser University** with Jie Liang, working on learned image and video coding.

After finishing my PhD in 2023, I stayed at Simon Fraser University as a postdoctoral researcher with Jie Liang and Zhenman Fang. Alongside data compression, I worked on privacy-preserving human activity recognition in collaboration with AltumView.

I joined the **University of British Columbia** in September 2025 as a postdoctoral researcher in Xiaoxiao Li’s TEA Group. My current work focuses on the mechanistic interpretability of vision-language models. I use ideas from information theory to study what visual information model components encode and how that information shapes their answers.

## News

- **Nov 2026** · [ChWDTA](#chwdta) was accepted for publication in *IEEE Transactions on Image Processing*.
- **Oct 2026** · We released [VLMProbe](#vlmprobe), an open-source library for studying how vision-language models use visual information. [Code](https://github.com/ubc-tea/vlm-probe)
- **Sep 2025** · I joined the [TEA Group](https://tea.ece.ubc.ca/) at UBC as a postdoctoral researcher.
- **2024** · My project on privacy-preserving activity recognition received a [Health Research BC–Mitacs Industry-Based Award](https://www.healthresearchbc.ca/our-impact/funded-research/haisheng-fu/).

## Selected publications

### ChWDTA

**Channel-wise Wavelet-Domain Transformer Attention and Entropy Modeling for Learned Image Compression**  
*IEEE Transactions on Image Processing · Accepted, 2026*

We applied wavelet transforms along feature channels within windowed attention and before entropy coding. In the preprint, the eight-slice model reduced BD-rate by 17.8–22.6% against VVC-Intra across Kodak, CLIC Professional Validation, and Tecnick. The four-slice model trades a small part of those gains for faster coding.

[Preprint](https://arxiv.org/abs/2606.00111) · [Code](https://github.com/fengyurenpingsheng/ChWDTA-Learned-image-compression)

### VLMProbe

**VLMProbe: An Open-source Library for VLM Probing and Interpretation**  
*arXiv · 2026*

I co-authored VLMProbe, which brings lens readouts, attention attribution, causal interventions, and sparse autoencoder analysis into one interface. Our experiments compare these methods and show that attribution scores can disagree with the measured effects of intervening on model activations.

[Preprint](https://arxiv.org/abs/2610.33072) · [Code](https://github.com/ubc-tea/vlm-probe)

### FEDS

**Feature and Entropy-Based Distillation Strategy for Efficient Learned Image Compression**  
*Pattern Recognition · Vol. 183, 2027*

We trained a smaller codec to match a larger one by transferring intermediate features and prioritizing channels that are expensive to encode. The student used about 63% fewer parameters, with a BD-rate increase of 0.55–1.24% relative to its teacher across three datasets.

[Paper](https://doi.org/10.1016/j.patcog.2026.114767)

### Dual-Branch Learned Image Compression

**Dual-Branch Learned Image Compression with Conditional Entropy Modeling and Deformable Convolution-based Attention**  
*IEEE Transactions on Circuits and Systems for Video Technology · 2026*

The codec learns separate representations for image structure and fine detail. It decodes structure first and uses that information to predict the probabilities needed to code detail.

[Paper](https://doi.org/10.1109/TCSVT.2026.3742841)

### SELIC

**Semantic-Enhanced Learned Image Compression via High-Level Textual Guidance**  
*IEEE International Conference on Multimedia and Expo · 2025*

We used automatically generated image descriptions to guide compression. The encoder combines text and image features before quantization so that the decoder can reconstruct the image from a single bitstream.

[Paper](https://doi.org/10.1109/ICME59968.2025.11209028) · [Preprint](https://arxiv.org/abs/2504.01279)

### WeConvene

**Learned Image Compression with Wavelet-Domain Convolution and Entropy Model**  
*European Conference on Computer Vision · 2024*

We added discrete wavelet transforms to a convolutional codec and its entropy model. Coding low-frequency coefficients first lets the model use them to predict the probabilities of high-frequency details.

[Paper](https://doi.org/10.1007/978-3-031-72973-7_3) · [Code](https://github.com/fengyurenpingsheng/WeConvene)

### Fast and High-Performance Learned Image Compression

**Fast and High-Performance Learned Image Compression With Improved Checkerboard Context Model, Deformable Residual Module, and Knowledge Distillation**  
*IEEE Transactions on Image Processing · 2024*

A checkerboard context model processes positions in parallel, while knowledge distillation reduces the work performed by the decoder. In the paper’s comparison with our 2023 GLLMM codec, this approach was about 20 times faster at encoding and 70–90 times faster at decoding.

[Paper](https://doi.org/10.1109/TIP.2024.3445737) · [Author manuscript](https://www.sfu.ca/~zhenman/files/J17-TIP2024-Fast-LIC.pdf)

### GLLMM

**Learned Image Compression with Discretized Gaussian-Laplacian-Logistic Mixture Model and Concatenated Residual Modules**  
*IEEE Transactions on Image Processing · 2023*

Combining Gaussian, Laplacian, and logistic distributions gives the entropy model more flexibility to estimate the probabilities of the symbols produced by the encoder.

[Paper](https://doi.org/10.1109/TIP.2023.3263099) · [Code](https://github.com/fengyurenpingsheng/Learned-image-compression-with-GLLMM)

[Full publication list on Google Scholar](https://scholar.google.com/citations?user=vGglk-EAAAAJ&hl=en)
