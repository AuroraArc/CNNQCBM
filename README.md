# Quantum Computing and ML for DFT Calculations in Proteins
The integration of machine learning and deep learning into quantum chemistry has opened new avenues for advancing 
density functional theory calculations. This presentation explores the application of a relatively new field of 
technology&mdash;quantum computing&mdash;to enhance DFT calculations, specifically for large molecular systems like proteins. Quantum 
computing has two distinct advantages: traditional computational approaches have struggled with the complexity and 
size of these systems, but quantum computing promises to overcome these limitations, and applying a model inherently 
quantum in nature, in theory, allows for better quantum prediction.

To implement this, I introduce a possible model, 
which takes a machine learning model called Linked Dynamic Graph Convolutional Neural Network (LDGCNN) to 
predict electronic densities on a point cloud. This architecture, known for its ability to capture local geometric 
relationships through dynamic graph construction and edge convolutions, robust feature extraction, and local context 
capabilities, can potentially be suitable for protein systems. By integrating a Quantum Circuit Born Machine (QCBM) to 
replace the output, we can produce an electronic density distribution. Leveraging the power of quantum computing, we 
aim to achieve more accurate and efficient DFT calculations, offering a novel approach to quantum systems and 
highlighting the potential of quantum computing in quantum chemistry.

## References

Qi, C. R., Yi, L., Su, H., & Guibas, L. J. (2017). PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space. https://arxiv.org/abs/1706.02413

Wang, Y., Sun, Y., Liu, Z., Sarma, S. E., Bronstein, M. M., & Solomon, J. M. (2019). Dynamic Graph CNN for Learning on Point Clouds. https://arxiv.org/abs/1801.07829

Zhang, K., Hao, M., Wang, J., de Silva, C. W., & Fu, C. (2019). Linked Dynamic Graph CNN: Learning on Point Cloud via Linking Hierarchical Features. https://arxiv.org/abs/1904.10014
