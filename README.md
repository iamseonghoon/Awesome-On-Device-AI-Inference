# Awesome-On-Device-AI-Inference 🔍📲
This list highlights academic work focused on running AI models efficiently on resource-constrained mobile devices, such as smartphones and edge devices. This repo references [Awesome-On-Device-AI-Systems](https://github.com/jeho-lee/Awesome-On-Device-AI-Systems). We categorize target devices into (1) **Edge Devices** (e.g., NVIDIA Jetson), (2) **Smartphones** (e.g., Snapdragon/Exynos), (3) and **Microcontrollers** for energy-harvesting or batteryless IoT devices, with a primary focus on research conducted for edge devices and smartphones.

### Single-DNN Inference on Microcontrollers
* [SenSys 2025] Lupe: Integrating the Top-down Approach with DNN Execution on Ultra-Low-Power Devices [(Paper)](https://people.cs.uchicago.edu/~myxiang/papers/lupe.pdf)
* [SenSys 2024] Intermittent Inference: Trading a 1% Accuracy Loss for a 1.9 x Throughput Speedup [(Paper)](https://dl.acm.org/doi/10.1145/3666025.3699364)
* [SenSys 2024] Fast-Inf: Ultra-Fast Embedded Intelligence on the Batteryless Edge [(Paper)](https://dl.acm.org/doi/abs/10.1145/3666025.3699335)
* [MobiSys 2023] HarvNet: Resource-Optimized Operation of Multi-Exit Deep Neural Networks on Energy Harvesting Devices [(Paper)](https://dl.acm.org/doi/10.1145/3581791.3596845)


### Single-DNN Inference on Mobile CPU/GPU
**Application-specific**
* [AAAI 2025] E4: Energy-Efficient DNN Inference for Edge Video Analytics Via Early Exiting and DVFS [(Paper)](https://ojs.aaai.org/index.php/AAAI/article/view/32104)
  * Video analytics; Edge devices (NVIDIA Jetson)
* [MobiCom 2024] Panopticus: Omnidirectional 3D Object Detection on Resource-constrained Edge Devices [(Paper)](https://arxiv.org/abs/2410.01270)
  * 3D object detection with adaptive multi-branch inference; Edge devices (NVIDIA Jetson)
* [MobiSys 2023] OmniLive: Super-Resolution Enhanced 360° Video Live Streaming for Mobile Devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3581791.3596851)
  * Video super-resolution with adaptive inference; Smartphones (Snapdragon/Exynos)
* [MobiCom 2020] NEMO: enabling neural-enhanced video streaming on commodity mobile devices [(Paper)](https://dl.acm.org/doi/10.1145/3372224.3419185)
  * Video super-resolution; Smartphones (Snapdragon/Exynos)

**General**
* [TMC 2025] NeuroBalancer: Balancing System Frequencies With Punctual Laziness for Timely and Energy-Efficient DNN Inferences [(Paper)](https://ieeexplore.ieee.org/abstract/document/10819653)
  * Conventional DNNs; Smartphones (Snapdragon/Exynos)
* [ASPLOS 2024] SmartMem: Layout Transformation Elimination and Adaptation for Efficient DNN Execution on Mobile [(Paper)](https://dl.acm.org/doi/10.1145/3620666.3651384)
  * Transformers; Smartphones (Snapdragon/Exynos)
* [MobiCom 2024] Mobile Foundation Model as Firmware [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3649361)
  * Foundation model; Edge devices (NVIDIA Jetson) and Smartphones (Snapdragon/Exynos)
* [MobiCom 2022] Romou: Rapidly Generate High-Performance Tensor Kernels for Mobile GPUs [(Paper)](https://dl.acm.org/doi/10.1145/3495243.3517020)
  * Conventional DNNs; Smartphones (Snapdragon/Exynos)
* [MobiCom 2021] AsyMo: Scalable and Efficient Deep-Learning Inference on Asymmetric Mobile CPUs [(Paper)](https://dl.acm.org/doi/10.1145/3447993.3448625)
  * Conventional DNNs; Smartphones (Snapdragon/Exynos)

### Single-DNN Inference on Mobile NPU
* [IEEE TMC 2023] NAWQ-SR: A Hybrid-Precision NPU Engine for Efficient On-Device Super-Resolution [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution

### Single-DNN Inference on Heterogeneous Mobile Processors (CPU, GPU, NPU, etc.)
* [IEEE TMC 2024] Thermal-Aware Scheduling for Deep Learning on Mobile Devices with NPU [(Paper)](https://ieeexplore.ieee.org/document/10478860)
* [MobiCom 2024] Perceptual-Centric Image Super-Resolution using Heterogeneous Processors on Mobile Devices [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution; Smartphones (Snapdragon/Exynos)
* [IPSN 2021] Efficient Execution of Deep Neural Networks on Mobile Devices with NPU [(Paper)](https://dl.acm.org/doi/10.1145/3412382.3458272)
* [MobiCom 2019] MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/10.1145/3300061.3345455)
  * Single-image super-resolution


### Multi-DNN Inference on Mobile CPU/GPU
* [MobiSys 2024] Pantheon: Preemptible Multi-DNN Inference on Mobile Edge GPUs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3643832.3661878)
  * Edge devices (NVIDIA Jetson)
* [SenSys 2023] Miriam: Exploiting Elastic Kernels for Real-time Multi-DNN Inference on Edge GPU [(Paper)](https://dl.acm.org/doi/10.1145/3625687.3625789)
* [MobiSys 2022] CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538932)

### Multi-DNN Inference on Mobile NPU
* [HPCA 2021] Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling [(Paper)](https://ieeexplore.ieee.org/document/9407236)

### Multiple DNN Inference on Heterogeneous Mobile Processors (CPU, GPU, NPU, etc.)
* [MobiSys 2025] ARIA: Optimizing Vision Foundation Model Inference on Heterogeneous Mobile Processors for Augmented Reality [(Paper)]()
  * Vision foundation model for augmented reality (depth estimation, semantic segmentation, etc.); Smartphones (Snapdragon/Exynos)
* [PPoPP 2024] Shared Memory-contention-aware Concurrent DNN Execution for Diversely Heterogeneous SoCs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3627535.3638502)
  * Conventional DNNs
* [MobiSys 2023] NN-Stretch: Automatic Neural Network Branching for Parallel Inference on Heterogeneous Multi-Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3472381.3479910)
* [MobiSys 2022] Band: Coordinated Multi-DNN Inference on Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538948)

### Challenges
* [Mobile AI Workshop](https://ai-benchmark.com/workshops/mai/2025/)
