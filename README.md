# Visually Similar Product Recommendation

## Project Overview
This project implements a visually similar product recommendation system using deep learning and computer vision techniques. The system analyzes product images and metadata to identify and recommend visually similar items from an e-commerce fashion dataset.

## Dataset
The project uses a fashion e-commerce dataset containing:
- Product images
- Product metadata including:
  - Gender
  - Master category (Apparel, Accessories, Footwear, etc.)
  - Sub-category (Topwear, Bottomwear, Bags, Watches, etc.)
  - Article type
  - Base color
  - Season
  - Year
  - Usage type
  - Product display name

## Key Features
- **Data Preprocessing**: Merges image data with product metadata and filters out products with missing images
- **Exploratory Data Analysis**: Comprehensive visualization of product categories and distributions
- **Deep Learning Models**: Utilizes pre-trained CNN architectures (VGG16, ResNet50, DenseNet201, Xception) for feature extraction
- **Similarity Matching**: Implements cosine similarity and other distance metrics to find visually similar products
- **Real-time Recommendations**: Provides product recommendations based on visual similarity

## Technical Stack
- **Programming Language**: Python
- **Deep Learning Framework**: TensorFlow/Keras
- **Computer Vision**: Pre-trained CNN models (VGG16, ResNet50, DenseNet201, Xception)
- **Data Processing**: Pandas, NumPy
- **Visualization**: Plotly, Matplotlib
- **Image Processing**: OpenCV, Keras preprocessing

## Project Structure
- Data loading and preprocessing
- Exploratory data analysis and visualization
- Feature extraction using deep learning models
- Similarity computation and recommendation generation
- Model evaluation and performance analysis

## Installation & Setup
1. Clone the repository
2. Install required dependencies:
   ```
   pip install tensorflow pandas numpy matplotlib plotly opencv-python
   ```
3. Download the dataset and update file paths in the notebook

## Usage
1. Run the Jupyter notebook sequentially from top to bottom
2. The system will:
   - Load and preprocess the product data
   - Perform exploratory data analysis
   - Extract visual features from product images
   - Generate similarity matrices
   - Provide recommendations for query products

## Applications
- E-commerce product recommendation systems
- Visual search engines
- Fashion item matching and styling suggestions
- Inventory management and product categorization

## Key Insights
- The dataset contains diverse fashion categories with Topwear being the most prevalent
- Multiple deep learning architectures are compared for optimal feature extraction
- Visual similarity goes beyond basic category matching to capture style, color, and design elements

## Future Enhancements
- Integration of textual metadata with visual features
- Real-time recommendation API
- Multi-modal similarity scoring
- User preference learning and personalization
- Deployment as a web service

This project demonstrates the practical application of computer vision and deep learning in building intelligent product recommendation systems for e-commerce platforms.
