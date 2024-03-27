# Audio Classification Project

This project aims to classify audio files into different categories using Deep learning techniques. It includes a notebook for exploratory data analysis (EDA) and model building, as well as saved models and some test data.

## UrbanSound8k Dataset

The UrbanSound8k dataset is a popular dataset for audio classification tasks, containing 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, engine_idling, gun_shot, jackhammer, siren, and street_music. 

You can download the UrbanSound8k dataset from [here](https://urbansounddataset.weebly.com/urbansound8k.html).


## Folder Structure

The folder structure of the project is as follows:

```
├── saved_models/
│ ├── extracted_audio_features.csv
│ └── audio_classification.hdf5
├── test_data/
│ ├── file1.wav
│ ├── file2.wav
│ └── ...
└── audio_classification.ipynb
```


- `saved_models/`: Contains saved models and extracted audio features.
  - `extracted_audio_features.csv`: CSV file containing extracted features of audio files.
  - `audio_classification.hdf5`: HDF5 file containing the trained audio classification model.
- `test_data/`: Contains audio files for testing the trained models.
  - Audio files should have the `.wav` format.
- `audio_classification.ipynb`: Jupyter notebook containing EDA and model building process.

## Usage

1. **Exploratory Data Analysis (EDA)**:
   - Open the `notebook.ipynb` notebook in Jupyter or any compatible environment.
   - Explore the provided data, including extracted features and their distributions.
   - Perform any necessary preprocessing steps such as data cleaning, feature engineering, etc.

2. **Model Building**:
   - Follow the notebook to build, train, and evaluate machine learning models for audio classification.
   - The notebook may include steps such as data preprocessing, feature selection, model training, hyperparameter tuning, and model evaluation.

3. **Testing**:
   - Use the provided test data (`test_data/`) to test the trained models.
   - Predict the labels of test audio files using the trained models.
   - Evaluate the performance of the models based on the predictions.

## Dependencies

- Python 3.x
- Required libraries (numpy, pandas, scikit-learn, keras, etc.)
- Jupyter Notebook (for running the notebook)

## License

This project is licensed under the [MIT License](LICENSE).
