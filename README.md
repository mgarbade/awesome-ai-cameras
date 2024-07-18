# AI-Enhanced Cameras: Dedicated Hardware for On-Device Vision Processing

Welcome to a dedicated space for exploring and cataloging cameras equipped with hardware-based neural networks. These devices integrate convolutional neural networks (CNNs) directly onto hardware, paired with a camera sensor, facilitating high-speed image processing with minimal power consumption and no need for extensive external data transmission.

## Device List Overview
- [IDS NXT - Ambarella](#ids-nxt-family-with-built-in-fpga--ambarella)
- [Firefly-DL](#firefly-dl)
- [Luxonis OAK-1](#luxonis-oak-1)
- [SCAMP5](#scamp5)
- [Sony IMX500](#sony-imx500)
- [Sony IMX501](#sony-imx501)

## No Camera sensor / Only AI Chip
- [Nvidia Jetson Nano](#nvidia-jetson-nano)
- [BrainChip - Akida](#brainchip---akida)
- [Qualcomm QCS8250](#qualcomm-qcs8250)
- [Google EdgeTPU](#google-edgetpu)
- [Intel Neural Stick2 - Movidius Myriad X VPU](#intel-neural-stick2---movidius-myriad-x-vpu)

## Why Hardware-Based AI Cameras?
Integrating AI directly into camera hardware allows for:
- **High Frame Rates & Low Bandwidth**: Streamline data processing directly on the device, reducing the need for data transfer.
- **Low Power Consumption**: Ideal for battery-operated or remote devices.
- **No Communication Overhead**: Operates independently of network constraints.
- **Simplified Deployment**: No advanced programming required, making it accessible for various applications.

## Devices with Camera Sensor

### IDS NXT family with built in FPGA / Ambarella
- **TODO**: Research specs  
- [Website](https://www.edge-ai-vision.com/2023/11/new-class-of-edge-ai-industrial-cameras-allows-ai-overlays-in-live-video-streams/)

### Firefly-DL
- **TODO**: Research specs  
- [Website](https://www.flir.eu/products/firefly-dl/)

### Luxonis OAK-1
- **TODO**: Research specs  
- [Website](https://shop.luxonis.com/collections/oak-cameras-1)

### SCAMP5
- **Capabilities**:
  - Digit recognition, hand gesture recognition, lip reading
  - 10,000 FPS
  - Analogue signal processing (before DAC)
  - Does not support MMADDs
  - Instead uses additions, subtractions, binary operations (needs specialized CNN architecture)
- **Literature**:
  - "A Camera that CNNs" (2019) [Paper](https://arxiv.org/abs/1909.05647), [Video](https://www.youtube.com/watch?v=grlIwYMcmG0&t=69s&ab_channel=StanfordComputationalImagingLab)
  - PixelRNN (2024) [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/So_PixelRNN_In-pixel_Recurrent_Neural_Networks_for_End-to-end-optimized_Perception_with_Neural_CVPR_2024_paper.pdf)

### Sony IMX500
- **Capabilities**: 
  - Human pose estimation, semantic segmentation
- **Literature**: 
  - [Website](https://developer.sony.com/imx500)
  - [Video - Human Pose Estimation](https://www.youtube.com/watch?v=V6ePnGZlFT8&ab_channel=lucanestola)

## No Camera sensor / Only AI Chip

### Nvidia Jetson Nano
- [Details TBD]

### Brainchip - Akida
- [Website](https://brainchip.com/akida-foundations/), [Video](https://www.youtube.com/watch?v=yY_raEGgka0&ab_channel=EdgeAIandVisionAlliance)

### Qualcomm QCS8250
- [Details TBD]

### Google EdgeTPU
- [Details TBD]

### Intel Neural Stick2 - Movidius Myriad X VPU
- [Details TBD]

## Further Reading and Resources
- [Edge AI Vision Alliance](https://www.edge-ai-vision.com/) is a website and community trying to bring together companies, customers, and everyone interested in AI on edge devices.

## Contributing
We encourage the community to contribute by adding new devices or updating existing entries. Please provide detailed information including device capabilities, specifications, use cases, and official links.

## Updates and Maintenance
This list is maintained by community contributions and curated by Martin Garbade. Updates are made regularly to ensure accuracy and relevance.

Join us in documenting the evolution of AI cameras and pushing the boundaries of what's possible with on-device processing!

## Tags
`ai`, `machine-learning`, `embedded-systems`, `hardware-acceleration`, `computer-vision`
