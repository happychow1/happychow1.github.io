---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# ZHOU Yanpeng's Resume

**Contact Information**  
TEL: (86)15756224157  
EMAIL: YZHOU037@e.ntu.edu.sg  

---

## Education Background

**Nanyang Technological University**  
Major: Computer Control and Automation  
Master's Degree (Jan. 2021 - Feb. 2022)  
GPA: 4.75/5.0  
Research Areas: Artificial Intelligence, Computer Vision, Human-Computer Interaction, Natural Language Processing  

**University of Electronic Science and Technology of China**  
Major: Electronic Science and Technology  
Bachelor's Degree (Sep. 2016 - Jun. 2020)  
GPA: 3.76/4.0  
Research Areas: Electronic Information  

---

## Work Experience

**Huawei Noah's Ark Lab**  
Position: Algorithm Researcher  
Duration: Jul. 2022 - Present  

### Multimodal Pretrained Large Model

- **PanGu Multimodal Large Model Encoder Training (Jan. 2024 - Dec. 2024)**:  
  Explored and constructed the visual Encoder-UNIT of the PanGu multimodal large model, achieving multi-resolution and multi-task joint training for natural and document images. This approach enables simultaneous global semantic understanding (for natural images) and local fine-grained perception (for document images). To further enhance the encoder's capability for wide visual scene perception, a systemized scale-up scheme was proposed, which includes parameter expansion training and enhanced data sampling. The UNIT-0.6B model achieved 1%-10% higher accuracy in image classification and segmentation compared to models with the same parameters (e.g., OpenCLIP), 2%-12% higher accuracy in document OCR compared to expert models (e.g., Nougat), and 1.2-2.4 times better performance in document understanding tasks. The UNIT_1B model supports native arbitrary resolution training and inference, with a 20% improvement over UNIT-0.6B. These achievements have been applied to all commercial versions of the PanGu multimodal large model, supporting multiple business departments such as Huawei Cloud, Vehicle BU, and Terminal Xiaoyi.

### Multimodal Agent

- **Long-Video Textual and Pictorial Summary Agent (Jun. 2024 - Oct. 2024)**:  
  Responsible for video textual and pictorial summarization, enabling concise summaries for both short videos (under 5 minutes) and long videos (hour-long meetings or classes). The data pipeline involved collecting, processing, and labeling video data. An innovative approach introduced repetition to quantify frame importance, achieving over 50% frame compression. By integrating CLIP and OCR, the system selected frames highly relevant to key points, achieving nearly 90% frame compression. The model was fine-tuned based on the PanGu multimodal model for video segmentation summarization and key frame selection. Evaluation metrics segmentation included summarization frame selection qualification rate and excellence rate, with the fine-tuned model achieving over 90% qualification rate.

- **Long-Document Textual and Pictorial Summary Agent(Oct. 2024 - Dec. 2024)**:  
  Responsible for summarizing long documents (5-80 pages, such as academic papers or financial reports) with textual and pictorial content. The data construction process innovatively incorporated image captions into the replacement text, improving illustration accuracy. Multiple data quality inspection standards were established to enhance user experience. The model was fine-tuned based on the PanGu multimodal large model for 32K and 128K long-document summarization. Evaluation metrics included illustration placement accuracy and key image recall rate, combining human annotation and GPT scoring for rapid evaluation. The model achieved a 90% illustration qualification rate and a 91% key image accuracy rate, which has been implemented in Huawei Terminal Xiaoyi.

### 3D Enthusiast

- **3D Understanding and Embodied Intelligence (Jan. 2024 - Dec. 2024)**:  
  - Utilized 3DGS as a new 3D representation modality in 3D pretraining models, achieving state-of-the-art (SOTA) performance in 3D object classification and recall tasks.  
  - Explored a 3D scene understanding pretraining large model based on 3D and 2D representations. Collected 400k scene data and constructed over 7 million spatial intelligence data points, achieving SOTA performance on multiple spatial intelligence benchmarks.  
  - Investigated a 4D input-based embodied intelligence pretraining large model. Established a robot action data collection process and achieved SOTA performance in multiple simulation environments (e.g., Libero, Calvin).

- **3D Face Modeling (Jan. 2023 - Dec. 2023)**:  
  Explored and studied a weakly supervised training framework for 3DMM face reconstruction algorithms, used for realistic face geometry reconstruction, cartoon character geometry priors, and initial values for single-frame and multi-frame geometry optimization algorithms. The framework incorporated semantic information with BlenderShape, a new recognition module, edge loss, and semi-supervised training methods. The algorithm achieved SOTA performance in coarse modeling (e.g., in the Asian face dataset FaceScape, the average reconstruction error was reduced compared to Deep3DFace and MICA, and it ranks first in the REALY benchmark for coarse modeling).

- **AIGC-3D (Jan. 2023 - Jun. 2023)**:  
  Explored and studied diffusion model-based text-to-high-precision geometry and texture generation. The results can be directly used in film and television rendering pipelines, significantly reducing the threshold for related artists and improving production efficiency. By inputting text, the system can generate fixed-topology geometry models with high-precision textures and materials, achieving results comparable to 3DMM-based face reconstruction algorithms.


## Published Papers

1. Haoyuan Li, Yanpeng Zhou, Tao Tang, Jifei Song, Yihan Zeng, Michael Kampffmeyer, Hang Xu, Xiaodan Liang. **UniGS: Unified Language-Image-3D Pretraining with Gaussian Splatting**. The Thirteenth International Conference on Learning Representations (ICLR), 2025.

2. Yi Zhu, Yanpeng Zhou, Chunwei Wang, Yang Cao, Jianhua Han, Lu Hou, Hang Xu. **UNIT: Unifying Image and Text Recognition in One Vision Encoder**. Neural Information Processing Systems (NeurIPS), 2024.

3. Zhou, Y., Wang, M., Gupta, M., Ambikapathi, A., Suganthan, P. N., & Ramasamy, S. (May 2022). **Investigating robustness of biological vs. backprop based learning**. In ICASSP 2022-2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 3533-3537). IEEE.

4. Yang, D., Zhou, Y., Zhang, Z., Li, T. J. J., & LC, R. (March 2022). **AI as an Active Writer: Interaction strategies with generated text in human-AI collaborative fiction writing**. In Joint Proceedings of the ACM IUI Workshops (Vol. 10). CEUR-WS Team.

5. Zhou, Y., Liu, Y., Li, Y., Jiang, R., Li, W., Zhao, W., ... & Zhou, P. (2020). **Flexible radiative cooling material based on amorphous alumina nanotubes**. Optical Materials Express, 10(7), 1641-1648.

6. Wenxin, L., Wangchen, Z., Yanpeng, Z., Yanning, L., Ya, L., Ruomei, J., ... & Longjiang, D. (2019). **Effect of deposition potential and concentration of electroactive substances on Bi2Te3 nanowires fabricated by electrochemical method**. Nanotechnology, 30(24), 245702.

7. Ming Nie, Chunwei Wang, Yanpeng Zhou, Yuanfan Guo, Jianhua Han, Hang Xu, Li Zhang. **KFFocus: Highlighting Keyframes for Enhanced Video Understanding**. Conference on Computer Vision and Pattern Recognition 2025. (under review)

8. Jiahui Zhang, Yurui Chen, Yueming Xu, Yanpeng Zhou, Xinyue Cai, Guowei Huang, Hang Xu, Xingyue Quan, Li Zhang. **4D-VLA: Spatiotemporal Vision-Language-Action Pretraining with Cross-Scene Calibration**. Conference on Computer Vision and
  

