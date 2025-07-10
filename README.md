# MSP-MAD: Multi-scale Metal Artifact Detection Network

MSP-MAD (Multi-scale physical metal artifact detector) is a metal artifact detection algorithm based on multi-scale physical properties of CT imaging. This algorithm can automatically identify metal implants in CT images and various artifacts they cause, including streak artifacts and beam hardening artifacts. This provides accurate localization for subsequent metal artifact reduction algorithms.

> ⚠️ **Note**: Due to patent applications and project confidentiality requirements, the MSP-MAD source code is currently unavailable.

> 🚀 **Update Date**: July 10, 2025

> 🚀 **Coming Soon**: MSP-MSD source code will be released in the future. Stay tuned!

⭐ If you're interested in this research, please follow and star this project, as this will continuously motivate us to become better!

## 🎯 Innovative Features

MSP-MAD algorithm has the following innovative advantages:

🔥1. **Multi-scale Analysis**
   - Innovative multi-scale feature extraction framework
   - Adaptive feature fusion strategy
   - Multi-level artifact feature modeling

🔥2. **Physical Property Modeling**
   - Based on CT imaging physics
   - Consideration of metal material properties
   - Artifact formation mechanism analysis

🔥3. **Intelligent Detection Mechanism**
   - Automated feature learning
   - Adaptive parameter adjustment
   - Robust detection strategy

🔥4. **Quantitative Assessment System**
   - Multi-dimensional scoring metrics
   - Objective artifact quantification
   - Standardized evaluation process

## 🎯 Effect Demonstration

The following animation demonstrates the actual detection effect of the MSP-MAD algorithm on CT pelvic images containing metal implants:

![Metal Artifact Detection](public/metal_artifact_animation.gif)

🧠 As shown, the algorithm accurately detects various artifacts caused by internal or external metal objects during tomographic scanning, and marks all areas containing metal artifacts (note: the initial green marking box is very small, so it's not very obvious in the image).

## 🎯 Application Value

- **Clinical Diagnosis Assistance**: Provides precise localization of metal artifacts, assisting doctors in making more accurate diagnoses
- **Treatment Planning Optimization**: Provides reference basis for radiotherapy planning
- **Image Quality Assessment**: Provides objective quantitative indicators for CT image quality control
- **Research Analysis Support**: Supports quantitative analysis needs in related medical imaging research

## 🎯 Usage

pip install -r requirements.txt

```python
from metal_artifact_detector import MSP_MAD

# Initialize detector
detector = MSP_MAD('metal_image.nii.gz')

# Process all slices
results = detector.process_all_slices()

# Visualize detection results for specific slice (optional)
detector.visualize_detection_results(slice_idx=50)
```

## 📝 License

This project is licensed under the Apache License 2.0 - see the [LICENSE.txt](LICENSE.txt) file for details.

Copyright Jiaqi Li

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
