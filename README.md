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

## Applications
- E-commerce product recommendation systems
- Visual search engines
- Fashion item matching and styling suggestions
- Inventory management and product categorization


## Future Enhancements
- Integration of textual metadata with visual features
- Real-time recommendation API
- Multi-modal similarity scoring
- User preference learning and personalization
- Deployment as a web service

<img width="1156" height="704" alt="image" src="https://github.com/user-attachments/assets/f4343cd2-12de-4b9f-9f0e-987e1796d873" />
<img width="1153" height="707" alt="image" src="https://github.com/user-attachments/assets/4afb9c65-e1e0-41e7-aa4e-ee4f3c772210" />
<img width="1150" height="701" alt="image" src="https://github.com/user-attachments/assets/bf45de9d-3033-4a55-ab76-d82d84c64961" />
<img width="1168" height="696" alt="image" src="https://github.com/user-attachments/assets/8f8acf85-d0ef-4fe5-bbee-b6f34c5605f2" />


