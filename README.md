# Formative-2_Data-Preprocessing
We are working with two real-world datasets that contain overlapping but different features. The goal is to augment, merge, and enhance the data while ensuring consistency in a machine learning pipeline.

1. **Data Augmentation**:
   - Missing values were handled using mean, median, mode, or predictive modeling.
   - Synthetic data was generated and transformations were applied to reduce skewness.

2. **Dataset Merging**:
   - Datasets were combined using `id_mapping.csv` to resolve indirect relationships.
   - New features like `Customer Engagement Score` and time-based metrics were engineered.

3. **Data Consistency Checks**:
   - Duplicate rows were removed and categorical values validated.
   - Statistical summarization provided insights into the dataset.
   - Feature selection algorithm (SelectKBest) was applied to identify the top 10 features for machine learning.

## Report and Video
- **Report**: The detailed workflow, challenges, and team contributions are documented in `Summary_Report.pdf`.
- **Video Walkthrough**: The link to the video is provided here https://youtu.be/6AM59Pw5AsQ 

## How to Run
### Clone the Repository
```bash
git clone https://github.com/eadewusic/Formative-2_Data-Preprocessing.git
cd Formative-2_Data-Preprocessing
```
### Set up environment
Install the required libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
### Run the Notebook
1. Open the `Formative2_DataPreprocessing_Group18.ipynb` notebook in Jupyter, Google Colab, or another compatible platform.
2. Execute the cells sequentially to replicate the preprocessing workflow.

## View the Outputs
The final datasets are saved in the `final_datasets` folder:
- `customer_transactions_augmented.csv` (Augmented dataset)
- `final_customer_data_group18.csv` (Merged dataset)
- `final_dataset_ready_group18.csv` (Fully preprocessed dataset)

## Contributions
- **Eunice Adewusi**: Performed data augmentation and handled missing values (Part 1).
- **Christian Mutabazi**: Managed dataset merging and engineered new features (Part 2).
- **Theodora Omunizua**: Conducted data consistency checks, statistical analysis, and feature selection (Part 3).

## Bonus Challenge
The bonus challenge was successfully completed. A machine learning model was trained to predict customer spending behavior, and the trained model is saved in the `model` folder as `bonusmodel.joblib`.
