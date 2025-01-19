# Cervical Spine Fracture Detection using 2.5D CNN, UNet, BiGRU, and Attention Mechanisms

## Overview
This repository contains the implementation of an AI model designed to detect cervical spine fractures from medical imaging data. The model leverages a combination of **2.5D CNN**, **UNet**, **Bidirectional Gated Recurrent Units (BiGRU)**, and **Attention Mechanisms** to achieve accurate and interpretable fracture detection. The project is inspired by the **RSNA 2022 Cervical Spine Fracture Detection Challenge**, which aimed to develop AI models to assist radiologists in identifying and localizing cervical spine fractures from CT scans.

## Key Features
- **2.5D CNN**: Captures both spatial and temporal features from medical imaging data, enabling the model to learn from multi-slice CT scans effectively.
- **UNet**: Provides precise segmentation of fracture regions, allowing for detailed localization of fractures.
- **BiGRU**: Enhances the model's ability to capture sequential dependencies in the data, improving performance.
- **Attention Mechanisms**: Increases interpretability by highlighting the most relevant regions of the input data for fracture detection.

## Impact
This model serves as a robust tool for the early and accurate detection of cervical spine fractures, aiding radiologists in diagnosis and treatment planning. By automating fracture detection, the model can help reduce diagnostic errors, improve patient outcomes, and streamline clinical workflows.

---

## Dataset
The dataset used in this project is sourced from the **RSNA 2022 Cervical Spine Fracture Detection Challenge**. It includes approximately **3,000 CT studies** annotated by spine radiology specialists from the **American Society of Neuroradiology (ASNR)** and the **American Society of Spine Radiology (ASSR)**. The annotations indicate the presence, vertebral level, and location of cervical spine fractures.

For more details about the dataset, visit the [RSNA Challenge Page](https://www.rsna.org/).

---

## Model Architecture
The model architecture combines the following components:
1. **2.5D CNN**: Extracts spatial and temporal features from multi-slice CT scans.
2. **UNet**: Performs precise segmentation of fracture regions.
3. **BiGRU**: Captures sequential dependencies in the extracted features.
4. **Attention Mechanisms**: Focuses on the most relevant regions for fracture detection.

---

## Installation
To set up the environment and run the code, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Youssef-Ashraf71/Cervical-Spine-Fracture-Detection.git
   cd cervical-spine-fracture-detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset**:
   - Visit the [RSNA Challenge Page](https://www.rsna.org/) to download the dataset.
   - Place the dataset in the `data/` directory.

---

## Acknowledgments
This project is based on the **RSNA 2022 Cervical Spine Fracture Detection Challenge**. We thank the **American Society of Neuroradiology (ASNR)** and the **American Society of Spine Radiology (ASSR)** for providing the annotated dataset and organizing the competition.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
## Contributions

All team members contributed equally to data collection, preprocessing, model selection, training, evaluation, and result interpretation.
### Team Members

- Abdulrahman Emad  
  Systems and Biomedical Engineering, Cairo University  
  Email: abdulrahman.masoud02@eng-st.cu.edu.eg

- Youssef Ashraf Mohammed  
  Systems and Biomedical Engineering, Cairo University  
  Email: youssef.aziz02@eng-st.cu.edu.eg

- Mourad Magdy  
  Systems and Biomedical Engineering, Cairo University  
  Email: murad.ibrahim02@eng-st.cu.edu.eg

- Mariam Ahmed Said  
  Systems and Biomedical Engineering, Cairo University  
  Email: maryam.abdulmajeed01@eng-st.cu.edu.eg. 

