https://drive.google.com/file/d/1Ob7yMMt3WDqUOgAZcgE0325MejBNQVA0/view?usp=share_link

# Plant Species Classification and Disease Detection Using Hybrid Model

## Introduction
Agriculture plays a vital role in feeding the world’s population and contributes significantly to a nation’s economy. However, plant diseases pose a major challenge, severely impacting crop yields. Early detection and identification of plant diseases are critical to ensuring food security and maintaining ecosystem balance. 

Accurately detecting plant species can help prevent diseases by following appropriate practices. With advancements in deep learning, we can now assist in detecting plant species and their associated diseases. This project aims to leverage Convolutional Neural Networks (CNN) to analyze plant images.

---

## Research Gap
1. **Efficiency and Scalability**  
   - Existing models prioritize accuracy but often overlook real-time efficiency and scalability.
   - There is a gap in balancing accuracy with in-field performance.

2. **Dual-Task Classification**  
   - Most studies focus on either species identification or disease detection.
   - The integration of both tasks in a single model remains underexplored.

3. **Background Complexity**  
   - Models often require uniform image backgrounds.
   - This limitation restricts their usability in natural, complex environments without additional image processing.

---

## Objectives
- Develop a hybrid deep learning model leveraging **VGG16, ResNet101, and DenseNet121** for feature extraction to identify plant species and diseases accurately.
- Integrate **attention mechanisms** to enhance focus on disease-affected areas in plant images, improving classification accuracy and model interpretability.
- Optimize the model architecture for efficient training on large-scale plant image datasets, ensuring **real-time disease detection** in agricultural fields.

## Architecture
<img width="1324" alt="Screenshot 2025-02-14 at 1 21 26 AM" src="https://github.com/user-attachments/assets/46a812a5-9555-4cef-abc9-7e130faf1eed" />

## Proposed Methodology
### Feature Extraction
- **ResNet101**: Uses residual connections for deep learning features, addressing vanishing gradients.
- **VGG16**: Captures fine details with small filters, enhancing spatial representation.
- **DenseNet121**: Employs dense connections for efficient feature reuse and improved gradient flow.
- **Combined Strengths**: Leverages the unique advantages of each network for comprehensive feature representation.

### Attention Mechanism
- **Prioritizes Important Features**: Highlights disease indicators.
- **Improves Interpretability**: Indicates which features influence predictions.
- **Enhances Robustness**: Adapts to variations in leaf appearance.
- **Dynamic Weighting**: Assigns weights based on feature significance.

---

## Dataset
| Sr No. | Dataset Name | Description | #Classes | #Images per Class |
|--------|-------------|-------------|---------|------------------|
| 1 | India Soybean Dataset | Data collected from Pune, Satara, etc., in Maharashtra. Contains healthy and insect-damaged soybean leaves. Used for disease detection. | 6 | 10-200 |
| 2 | Swedish Dataset | Labeled dataset used for species classification. Contains one-side leaf images with a white background. | 15 | 75 |

---

## Results
<img width="1278" alt="Screenshot 2025-02-14 at 1 22 07 AM" src="https://github.com/user-attachments/assets/23732381-c9ff-4fcd-8851-a9a15204aec4" />

<img width="758" alt="Screenshot 2025-02-14 at 1 22 23 AM" src="https://github.com/user-attachments/assets/dd0e8ce2-3bb6-4a0d-8b77-0e32107a3074" />
<img width="1284" alt="Screenshot 2025-02-14 at 1 22 36 AM" src="https://github.com/user-attachments/assets/7ced99e3-3875-4dc9-ba59-8180827f9bfb" />
<img width="726" alt="Screenshot 2025-02-14 at 1 22 52 AM" src="https://github.com/user-attachments/assets/569f6878-a5c0-4733-8159-c3879544681d" />

---

## Conclusion
In this project, we have developed a robust deep-learning model capable of accurately detecting diseases from leaf images and classifying similar-looking plant species. Using architectures such as **ResNet, DenseNet, and VGG**, we have ensured precise classification.

We aim to **reduce computational costs** while maintaining high accuracy through efficient feature extraction. The model's ability to generalize across various plant species and diseases demonstrates its potential for real-world agricultural applications.

Future work may involve expanding the model to include a broader variety of plant species and diseases, as well as exploring **real-time deployment** for practical use by farmers and agricultural professionals.

---

## References
1. Bathula, N., Prasath, R. & Praveen Joe, I.R., 2024. An automatic classification framework for identifying plant leaf diseases using multi-scale feature fusion-based adaptive deep network. Biomedical Signal Processing and Control, 95(Part A), p.106316. [DOI](https://doi.org/10.1016/j.bspc.2024.106316)
2. Wu, H., Fang, L., Yu, Q. & Yang, C., 2024. Composite descriptor based on contour and appearance for plant species identification. Engineering Applications of Artificial Intelligence, 133(Part C), p.108291. [DOI](https://doi.org/10.1016/j.engappai.2024.108291)
3. Bai, Y. & Bai, X., 2024. Deep learning-based aquatic plant recognition technique and natural ecological aesthetics conservation. Crop Protection, 184, p.106765. [DOI](https://doi.org/10.1016/j.cropro.2024.106765)
4. Pan, B., Liu, C., Su, B., et al., 2024. Research on species identification of wild grape leaves based on deep learning. Scientia Horticulturae, 327, p.112821. [DOI](https://doi.org/10.1016/j.scienta.2023.112821)
5. Sachar, S., Kumar, A. 2024. A novel transfer learning-based approach for plant species prediction using leaf images. Multimedia Tools and Applications, 83, 40323–40336. [DOI](https://doi.org/10.1007/s11042-023-17311-8)
6. Barhate, D., Pathak, S. & Dubey, A.K., 2023. Hyperparameter-tuned batch-updated stochastic gradient descent: Plant species identification using hybrid deep learning. Ecological Informatics, 75, p.102094. [DOI](https://doi.org/10.1016/j.ecoinf.2023.102094)
7. Reis, H.C. & Turk, V., 2024. Potato leaf disease detection with a novel deep learning model based on depthwise separable convolution and transformer networks. Engineering Applications of Artificial Intelligence, 133 (Part C), p.108307. [DOI](https://doi.org/10.1016/j.engappai.2024.108307)
8. Sharma, S. & Vardhan, M., 2024. MTJNet: Multi-task joint learning network for advancing medicinal plant and leaf classification. Knowledge-Based Systems, 299, p.112147. [DOI](https://doi.org/10.1016/j.knosys.2024.112147)
9. Oskar J. O. Söderkvist, 2001. “Computer vision classification of leaves from Swedish trees,” Linköping University. [Thesis]
10. Kotwal, Jameer; Kashyap, Ramgopal, 2023. “An India soybean leaf dataset,” Mendeley Data, V1. [DOI](10.17632/bshkvgbzpt.1)

---
