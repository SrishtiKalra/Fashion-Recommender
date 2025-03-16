# Fashion?! 🛍️

**Fashion?!** is an innovative tool designed to revolutionize how you approach style. Our objective is to empower you with confidence and convenience. Gone are the days of staring blankly into your closet, unsure of what to wear. We analyze your existing clothes and suggest stylish combinations effortlessly. 
More information can be found on this website: https://srishti1007sk.wixsite.com/fashion-recommender

## Features

- **Personalized Outfit Recommendations**: Analyze your wardrobe to suggest stylish combinations.
- **Multi-layered Feature Extraction**: Utilizes ResNet architecture with Global Average Pooling (GAP) for relevant feature extraction.
- **Visual Semantic Embedding**: Integrates visual and textual data for a unified feature space.
- **Pairwise Comparison**: Compares features across layers for similarity and difference assessment.
- **Diagnosis via Gradients**: Uses backpropagation gradients to pinpoint influential features.

## Tech Stack

- **Programming Languages**: Python
- **Frameworks & Libraries**: Dash, TensorFlow, PyTorch, ResNet
- **Dataset**: Polyvore-T

## Dataset

We use the [Polyvore-T dataset](https://www.kaggle.com/datasets/dnepozitek/maryland-polyvore-images/data) for training and testing. This dataset includes type-labeled fashion items, facilitating the training of type-specific compatibility assessments.

## Setup Instructions

### Prerequisites

Ensure you have the following installed:

- Python (>= 3.7)
- TensorFlow
- PyTorch
- Dash
- Other dependencies listed in `requirements.txt`

### Installation & Running Locally

1. **Clone the Repository**

   ```sh
   git clone https://github.com/yourusername/fashion.git
   cd fashion
