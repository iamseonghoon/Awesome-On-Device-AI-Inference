# Awesome-On-Device-AI-Inference 🔍📲
This list highlights academic work focused on running AI models efficiently on resource-constrained mobile devices, including (1) **edge devices** (e.g., NVIDIA Jetson), (2) **smartphones** (e.g., Snapdragon/Exynos), (3) and **microcontrollers** for energy-harvesting or batteryless IoT devices, with a primary focus on research conducted for edge devices & smartphones. This repo references [Awesome-On-Device-AI-Systems](https://github.com/jeho-lee/Awesome-On-Device-AI-Systems) by [Jeho Lee](https://jeho-lee.github.io/). 

### A-1. Single-DNN Inference on Single Mobile Processors
**General DNN inference**
* [MLSys 2025] AWQ: Activation-aware Weight Quantization for On-Device LLM Compression and Acceleration [(Paper)](https://proceedings.mlsys.org/paper_files/paper/2024/hash/42a452cbafa9dd64e9ba4aa95cc1ef21-Abstract-Conference.html)
  * LLM; Desktop & edge devices; GPU
* [MLSys 2025] MAS-Attention: Memory-Aware Stream Processing for Attention Acceleration on Resource-Constrained Edge Devices [(Paper)](https://arxiv.org/abs/2411.17720)
  * Attention-based NN; Edge devices; NPU
* [MLSys 2025] Efficient LLM Inference using Dynamic Input Pruning and Cache-Aware Masking [(Paper)](https://arxiv.org/abs/2412.01380)
  * LLM; Smartphones; NPU (Simulation)
* [ASPLOS 2025] Fast On-device LLM Inference with NPUs (llm.npu) [(Paper)](https://dl.acm.org/doi/10.1145/3669940.3707239)
  * LLM; Smartphones; NPU
* [IEEE TMC 2025] NeuroBalancer: Balancing System Frequencies With Punctual Laziness for Timely and Energy-Efficient DNN Inferences [(Paper)](https://ieeexplore.ieee.org/abstract/document/10819653)
  * CNN; Smartphones; GPU
* [ASPLOS 2024] SmartMem: Layout Transformation Elimination and Adaptation for Efficient DNN Execution on Mobile [(Paper)](https://dl.acm.org/doi/10.1145/3620666.3651384)
  * CNN, Transformer, and LLM; Smartphones; GPU
* [MobiCom 2024] FlexNN: Efficient and Adaptive DNN Inference on Memory-Constrained Edge Devices [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3649391)
  * CNN; Smartphones; CPU
* [MobiCom 2024] Mobile Foundation Model as Firmware [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3649361)
  * Foundation model; Edge devices & smartphones; CPU or GPU
* [MobiSys 2024] Empowering In-Browser Deep Learning Inference on Edge Devices with Just-in-Time Kernel Optimization [(Paper)](https://dl.acm.org/doi/10.1145/3643832.3661892)
  * Transformer; Smartphones & laptops; (Web)GPU
* [ASPLOS 2023] STI: Turbocharge NLP Inference at the Edge via Elastic Pipelining [(Paper)](https://dl.acm.org/doi/10.1145/3575693.3575698)
  * NLP (BERT); Edge devices; CPU or GPU
* [MobiCom 2022] Romou: Rapidly Generate High-Performance Tensor Kernels for Mobile GPUs [(Paper)](https://dl.acm.org/doi/10.1145/3495243.3517020)
  * CNN; Smartphones; GPU
* [MobiCom 2022] NeuLens: Spatial-based Dynamic Acceleration of Convolutional Neural Networks on Edge [(Paper)](https://dl.acm.org/doi/abs/10.1145/3495243.3560528)
  * CNN; Edge devices; GPU
* [MICRO 2022] GCD2: A Globally Optimizing Compiler for Mapping DNNs to Mobile DSPs [(Paper)](https://ieeexplore.ieee.org/document/9923837)
  * CNN and GAN; Smartphones; DSP (NPU)
* [MobiCom 2021] AsyMo: Scalable and Efficient Deep-Learning Inference on Asymmetric Mobile CPUs [(Paper)](https://dl.acm.org/doi/10.1145/3447993.3448625)
  * CNN and RNN; Smartphones; CPU
* [PLDI 2021] DNNFusion: Accelerating Deep Neural Networks Execution with Advanced Operator Fusion [(Paper)](https://dl.acm.org/doi/10.1145/3453483.3454083)
  * CNN and Transformer; Smartphones; CPU or GPU

**Application-specific optimization**
* [MobiSys 2025] ARIA: Optimizing Vision Foundation Model Inference on Heterogeneous Mobile Processors for Augmented Reality (To Appear)
  * Vision foundation model for AR; Smartphones
* [AAAI 2025] E4: Energy-Efficient DNN Inference for Edge Video Analytics Via Early Exiting and DVFS [(Paper)](https://ojs.aaai.org/index.php/AAAI/article/view/32104)
  * Video analytics; Edge devices; GPU
* [MobiCom 2024] Panopticus: Omnidirectional 3D Object Detection on Resource-constrained Edge Devices [(Paper)](https://arxiv.org/abs/2410.01270)
  * 3D object detection; Edge devices; GPU
* [MobiSys 2023] OmniLive: Super-Resolution Enhanced 360° Video Live Streaming for Mobile Devices [(Paper)](https://dl.acm.org/doi/abs/10.1145/3581791.3596851)
  * Video super-resolution; Smartphones; GPU
* [IEEE TMC 2023] NAWQ-SR: A Hybrid-Precision NPU Engine for Efficient On-Device Super-Resolution [(Paper)](https://ieeexplore.ieee.org/iel7/7755/4358975/10066526)
  * Single-image super-resolution; Smartphones; NPU
* [EuroSys 2022] LiteReconfig: Cost and Content Aware Reconfiguration of Video Object Detection Systems for Mobile GPUs [(Paper)](https://dl.acm.org/doi/10.1145/3492321.3519577)
  * Video analytics; Edge devices; GPU
* [UbiComp 2022] Efficient On-Device Visual Question Answering [(Paper)](https://dl.acm.org/doi/10.1145/3534619)
  * Visual question answering; Edge devices & smartphones; GPU
* [MobiCom 2021] Flexible High-Resolution Object Detection on Edge Devices with Tunable Latency [(Paper)](https://dl.acm.org/doi/10.1145/3447993.3483274)
  * Object detection; Edge devices; GPU
* [MobiCom 2020] NEMO: enabling neural-enhanced video streaming on commodity mobile devices [(Paper)](https://dl.acm.org/doi/abs/10.1145/3372224.3419185)
  * Video super-resolution; Smartphones; GPU

### A-2. Single-DNN Inference on Heterogeneous Mobile Processors
**General DNN inference**
* [SOSP 2025] HeteroLLM: Accelerating Large Language Model Inference on Mobile SoCs with Heterogeneous AI Accelerators [(Paper)](https://arxiv.org/abs/2501.14794)
  * LLM; Smartphones; CPU + GPU + NPU
* [EuroSys 2025] Flex: Fast, Accurate DNN Inference on Low-Cost Edges Using Heterogeneous Accelerator Execution [(Paper)](https://dl.acm.org/doi/10.1145/3689031.3696067)
  * Smartphones; CPU + GPU + NPU (TPU/DSP)
* [arXiv 2024] PowerInfer-2: Fast Large Language Model Inference on a Smartphone [(Paper)](https://arxiv.org/abs/2406.06282)
  * LLM; Smartphones; CPU + NPU
* [IEEE TMC 2024] Thermal-Aware Scheduling for Deep Learning on Mobile Devices with NPU [(Paper)](https://ieeexplore.ieee.org/document/10478860)
  * CNN; Smartphones; GPU + NPU 
* [ICDE 2023] EdgeNN: Efficient Neural Network Inference for CPU-GPU Integrated Edge Devices [(Paper)](https://ieeexplore.ieee.org/document/10184528)
  * CNN; Edge devices; CPU + GPU
* [ATC 2023] Decentralized Application-Level Adaptive Scheduling for Multi-Instance DNNs on Open Mobile Devices [(Paper)](https://www.usenix.org/conference/atc23/presentation/sung)
  * CNN; Smartphones; CPU + GPU 
* [IPSN 2021] Efficient Execution of Deep Neural Networks on Mobile Devices with NPU [(Paper)](https://dl.acm.org/doi/10.1145/3412382.3458272)
  * CNN; Smartphones; CPU + NPU 
* [EuroSys 2019] µLayer: Low Latency On-Device Inference Using Cooperative Single-Layer Acceleration and Processor-Friendly Quantization [(Paper)](https://dl.acm.org/doi/abs/10.1145/3302424.3303950)
  * CNN; Smartphones; CPU + GPU

**Application-specific optimization**
* [MobiCom 2024] Perceptual-Centric Image Super-Resolution using Heterogeneous Processors on Mobile Devices [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution; Smartphones; GPU + NPU
* [ICDE 2024] COUPLE: Orchestrating Video Analytics on Heterogeneous Mobile Processors [(Paper)](https://ieeexplore.ieee.org/abstract/document/10597847)
  * Video analytics (object detection); Smartphones; GPU + DSP (NPU)
* [IPSN 2023] PointSplit: Towards On-device 3D Object Detection with Heterogeneous Low-power Accelerators [(Paper)](https://dl.acm.org/doi/abs/10.1145/3583120.3587045)
  * 3D object detection; Edge devices; GPU + NPU
* [MobiCom 2019] MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/10.1145/3300061.3345455)
  * Single-image super-resolution; Smartphones; CPU + GPU + DSP (NPU)

### A-3. Single-DNN Inference across Multiple Mobile Devices
* [INFOCOM 2024] Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference [(Paper)](https://ieeexplore.ieee.org/abstract/document/10621342)
  * Transformer; Multiple edge devices; CPU + GPU

### B-1. Multi-DNN Inference on Single Mobile Processors
**General DNN inference**
* [IEEE TMC 2024] SwapNet: Efficient Swapping for DNN Inference on Edge AI Devices Beyond the Memory Budget [(Paper)](https://ieeexplore.ieee.org/abstract/document/10403957)
  * CNN; Edge devices; GPU
* [MobiSys 2024] Pantheon: Preemptible Multi-DNN Inference on Mobile Edge GPUs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3643832.3661878)
  * Edge devices; GPU
* [MICRO 2023] Sparse-DySta: Sparsity-Aware Dynamic and Static Scheduling for Sparse Multi-DNN Workloads [(Paper)](https://dl.acm.org/doi/10.1145/3613424.3614263)
  * CNN, Attention-based NN, and NLP; From smartphones to data centers; NPU (Simulation)
* [SenSys 2023] Miriam: Exploiting Elastic Kernels for Real-time Multi-DNN Inference on Edge GPU [(Paper)](https://dl.acm.org/doi/10.1145/3625687.3625789)
  * Edge devices; GPU
* [HPCA 2021] Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling [(Paper)](https://ieeexplore.ieee.org/document/9407236)
  * NPU (Simulation)
* [MobiCom 2021] LegoDNN: Block-grained Scaling of Deep Neural Networks for Mobile Vision [(Paper)](https://arxiv.org/abs/2112.09852)
  * Edge devices & smartphones; CPU or GPU
* [PerCom 2021] MASA: Responsive Multi-DNN Inference on the Edge [(Paper)](https://ieeexplore.ieee.org/document/9439111)
  * CNN; Edge devices (Raspberry Pi); CPU

**Application-specific optimization**
* [MobiCom 2020] Heimdall: Mobile GPU Coordination Platform for Augmented Reality Applications [(Paper)](https://dl.acm.org/doi/10.1145/3372224.3419192)
  * Augmented reality; Smartphones; GPU


### B-2. Multiple DNN Inference on Heterogeneous Mobile Processors
**General DNN inference**
* [PPoPP 2024] Shared Memory-contention-aware Concurrent DNN Execution for Diversely Heterogeneous SoCs (HaX-CoNN) [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3627535.3638502)
  * Edge devices; GPU + DLA (NPU)
* [SEC 2024] Elastic Execution of Multi-Tenant DNNs on Heterogeneous Edge MPSoCs [(Paper)](https://ieeexplore.ieee.org/document/10817905)
  * Smartphones; CPU + GPU + DSP (NPU)
* [MobiSys 2023] NN-Stretch: Automatic Neural Network Branching for Parallel Inference on Heterogeneous Multi-Processors [(Paper)](https://dl.acm.org/doi/abs/10.1145/3581791.3596870)
  * Smartphones; CPU + GPU + DSP (NPU)
* [MobiSys 2022] Band: Coordinated Multi-DNN Inference on Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538948)
  * Smartphones; CPU + GPU + DSP + NPU
* [MobiSys 2022] CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538932)
  * Smartphones; CPU + GPU
* [SenSys 2022] BlastNet: Exploiting Duo-Blocks for Cross-Processor Real-Time DNN Inference [(Paper)](https://dl.acm.org/doi/10.1145/3560905.3568520)
  * Edge devices; CPU + GPU
* [ACM TACO 2021] SLO-Aware Inference Scheduler for Heterogeneous Processors in Edge Platforms [(Paper)](https://dl.acm.org/doi/10.1145/3460352)
  * Smartphones, edge devices, and desktop computers; CPU + GPU + DSP (NPU)
* [RTSS 2019] Pipelined Data-Parallel CPU/GPU Scheduling for Multi-DNN Real-Time Inference [(Paper)](https://ieeexplore.ieee.org/document/9052147)
  * Edge devices (NVIDIA TX2) and desktop computers (Intel x86 Xeon); CPU + GPU


### C. Single-DNN Inference on Microcontrollers
* [SenSys 2025] Lupe: Integrating the Top-down Approach with DNN Execution on Ultra-Low-Power Devices (To Appear)
  * Ultra-low-power MCU (MSP430 series)
* [SenSys 2024] Intermittent Inference: Trading a 1% Accuracy Loss for a 1.9 x Throughput Speedup [(Paper)](https://dl.acm.org/doi/10.1145/3666025.3699364)
  * High-performance MCU (ARM Cortex-M series)
* [SenSys 2024] Fast-Inf: Ultra-Fast Embedded Intelligence on the Batteryless Edge [(Paper)](https://dl.acm.org/doi/abs/10.1145/3666025.3699335)
  * Ultra-low-power MCU (MSP430 series)
* [MobiSys 2023] HarvNet: Resource-Optimized Operation of Multi-Exit Deep Neural Networks on Energy Harvesting Devices [(Paper)](https://dl.acm.org/doi/10.1145/3581791.3596845)
  * Ultra-low-power MCU (MSP430 series)
* [ASPLOS 2023] Space-Efficient TREC for Enabling Deep Learning on Microcontrollers [(Paper)](https://dl.acm.org/doi/10.1145/3582016.3582062)
  * High-performance MCU (ARM Cortex-M series)
* [MLSys 2021] MicroNets: Neural Network Architectures for Deploying TinyML Applications on Commodity Microcontrollers [(Paper)](https://proceedings.mlsys.org/paper_files/paper/2021/hash/c4d41d9619462c534b7b61d1f772385e-Abstract.html)
  * High-performance MCU (ARM Cortex-M series)

### Challenges
* [Mobile AI Workshop](https://ai-benchmark.com/workshops/mai/2025/)
