# Awesome-On-Device-AI-Inference 🔍📲
This list highlights academic work focused on running AI models efficiently **on resource-constrained mobile devices**, such as smartphones and edge devices. This repo references [Awesome-Mobile-AI-Systems](https://github.com/your-org/Awesome-Mobile-AI-Systems).

### Single-DNN Inference on CPU/GPU
* [MobiCom 2024] Panopticus: Omnidirectional 3D Object Detection on Resource-constrained Edge Devices [(Paper)](https://arxiv.org/abs/2410.01270)
  * 3D object detection, adaptive multi-branch inference, Jetson devices
* [MobiSys 2023] OmniLive: Super-Resolution Enhanced 360° Video Live Streaming for Mobile Devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3581791.3596851)
  * Video super-resolution, adaptive inference, smartphones
* [MobiCom 2020] NEMO: enabling neural-enhanced video streaming on commodity mobile devices [(Paper)](https://dl.acm.org/doi/10.1145/3372224.3419185)
  * Video super-resolution, smartphones

### Single-DNN Inference on NPU
* [IEEE TMC 2023] NAWQ-SR: A Hybrid-Precision NPU Engine for Efficient On-Device Super-Resolution [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution

### Single-DNN Inference on Heterogeneous Processors (CPU, GPU, NPU, etc.)
* [MobiCom 2024] Perceptual-Centric Image Super-Resolution using Heterogeneous Processors on Mobile Devices [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution
* [IPSN 2021] Efficient Execution of Deep Neural Networks on Mobile Devices with NPU [(Paper)](https://dl.acm.org/doi/10.1145/3412382.3458272)
* [MobiCom 2019] MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/10.1145/3300061.3345455)
  * Single-image super-resolution


### Multi-DNN Inference on CPU/GPU
* [MobiSys 2024] Pantheon: Preemptible Multi-DNN Inference on Mobile Edge GPUs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3643832.3661878)
* [SenSys 2023] Miriam: Exploiting Elastic Kernels for Real-time Multi-DNN Inference on Edge GPU [(Paper)](https://dl.acm.org/doi/10.1145/3625687.3625789)
* [MobiSys 2022] CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538932)

### Multi-DNN Inference on NPU
* [HPCA 2021] Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling [(Paper)](https://ieeexplore.ieee.org/document/9407236)

### Multiple DNN Inference on Heterogeneous Processors (CPU, GPU, NPU, etc.)
* [MobiSys 2025] ARIA: Optimizing Vision Foundation Model Inference on Heterogeneous Mobile Processors for Augmented Reality [(Paper)]()
  * Vision foundation model, augmented reality (depth estimation, semantic segmentation, etc.), smartphones
* [PPoPP 2024] Shared Memory-contention-aware Concurrent DNN Execution for Diversely Heterogeneous SoCs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3627535.3638502)
* [MobiSys 2023] NN-Stretch: Automatic Neural Network Branching for Parallel Inference on Heterogeneous Multi-Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3472381.3479910)
* [MobiSys 2022] Band: Coordinated Multi-DNN Inference on Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538948)

### Challenges
* [Mobile AI Workship](https://ai-benchmark.com/workshops/mai/2025/)
