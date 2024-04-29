# Early Detection of Plant Diseases Using Imaging Data

## Introduction
This project utilizes Deep Learning (DL) to achieve early detection and classification of plant diseases, which is crucial for agricultural productivity and food security. Developed under the guidance of Professor Khaled Sayed for the DSCI-6011-02 Deep Learning course at the University of New Haven, this project showcases the use of pre-trained models like ResNet18 and custom CNN architectures to identify diseases in crops from imaging data.

## Project Structure
- **Datasets**: Includes the Rice Leaf Diseases and Tea Sickness datasets, which feature various classes of disease symptoms and healthy leaf images.
- 
https://www.kaggle.com/datasets/vbookshelf/rice-leaf-diseases

https://www.kaggle.com/code/stpeteishii/tea-leaf-disease-classify-monai-pytorch/input
- **Models**: Utilizes a variety of deep learning models, including ResNet18 and custom CNNs, tailored for the nuances of the specific datasets.
- **Training**: Models are trained with several augmentation techniques to enhance their generalization capabilities.
- **Deployment**: A user-friendly web interface created using Gradio, allowing users to upload images and receive disease classification predictions.

## Setup and Usage
1. **Clone the Repository**
    ⁠
   git clone https://github.com/hemasaikaja/DSCI_6011_02-FINAL-PROJECT.git
   cd your-project-folder
   
⁠ 2. **Install Requirements**
    ⁠
   pip install -r requirements.txt
   
⁠ 3. **Launch Jupyter Notebook**
    ⁠
   Run the code
   
⁠    This will also start the Gradio interface which can be accessed via a web browser to interact with the deployed models.

## Models and Performance
- **ResNet18 with Rice Leaf Diseases Dataset**: Achieves 100% accuracy across all classes.
- **ResNet18 with Tea Sickness Dataset**: Shows varied performance with overall accuracy of 62%.
- **Custom CNN with Tea Sickness Dataset**: Better adapts to complexities within the dataset, achieving 77% accuracy.
- **Custom CNN with Rice Leaf Diseases Dataset**: Struggles with some classes, yielding 50% accuracy.

## Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## Authors
- Hema Sai Kaja
- Venkata Sivannarayana Pavuluri

## Acknowledgments
Special thanks to Professor Khaled Sayed and the University of New Haven for supporting this project.

## References
Detailed citations and references of the datasets, models, and methodologies used are included within our project documentation.
 ⁠

This README.md file is structured to provide clarity and ease of access to all necessary information for anyone looking to understand or contribute to the project.
