# Mercari Price Suggestion Challenge - NLP Analysis

## About the Dataset
The dataset is part of the Mercari Price Suggestion Challenge on Kaggle. It contains approximately 1.5 million observations with multiple features for predicting item prices on the Mercari e-commerce platform.

## About the Challenge
Mercari is a popular e-commerce platform in Japan, similar to eBay. The challenge involves creating a process to predict prices for items that users want to sell on the Mercari platform.

## Dataset Features
- **train_id**: Unique identifier for each training observation
- **name**: Free text describing the item being sold
- **item_condition_id**: Condition of the item (1-5 scale)
- **category_name**: Category of the item with multiple sub-categories
- **brand_name**: Brand of the item
- **price**: Target variable - the price of the item in USD
- **shipping**: Shipping cost associated with the item
- **item_description**: Detailed description of the item

## Analysis Approach
1. **Data Preprocessing**: Cleaned and prepared the dataset for analysis
2. **Feature Engineering**: 
   - Split categories into sub-categories
   - Extracted brand information
   - Processed text data from item names and descriptions
3. **NLP Analysis**: Applied Natural Language Processing techniques to analyze text correlations with price
4. **Exploratory Data Analysis**: Comprehensive analysis of price distributions, brand patterns, and category relationships

## Model Approach
The analysis uses NLP-based techniques including:
- Text preprocessing and tokenization
- TF-IDF vectorization
- Word frequency analysis
- Statistical correlation analysis

## Installation and Setup

### Prerequisites
- Python 3.7 or higher
- pip package manager

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/manoharpavuluri/ml-mercari-NLP.git
   cd ml-mercari-NLP
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Download NLTK data (if not already downloaded):
   ```python
   import nltk
   nltk.download('punkt')
   nltk.download('stopwords')
   ```

4. Run the Jupyter notebook:
   ```bash
   jupyter notebook mercari.ipynb
   ```

## Dependencies
- pandas: Data manipulation and analysis
- numpy: Numerical computing
- seaborn: Statistical data visualization
- matplotlib: Plotting library
- plotly: Interactive plotting
- wordcloud: Word cloud generation
- nltk: Natural Language Processing toolkit
- scikit-learn: Machine learning library
- scipy: Scientific computing

## Project Structure
```
ml-mercari-NLP/
├── mercari.ipynb          # Main analysis notebook
├── requirements.txt       # Python dependencies
└── README.md             # Project documentation
```

## Results
The analysis provides insights into:
- Price distribution patterns across different categories
- Brand influence on pricing
- Text feature correlations with price
- Category-based pricing trends

## License
This project is for educational and research purposes.