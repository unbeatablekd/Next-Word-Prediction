---

# **Predict Next Word using LSTM**

This project demonstrates a machine learning application to predict the next word in a given sequence of text. Using a pre-trained Long Short-Term Memory (LSTM) model, the application suggests the most probable next word based on the input text. It leverages the power of deep learning and natural language processing (NLP) to understand linguistic patterns and predict accurate results.

---

## **Features**

- **Deep Learning with LSTM**: Utilizes an LSTM model trained on text data to predict the next word.
- **Tokenizer Support**: Processes input text using a tokenizer for sequence management.
- **Streamlit Interface**: Provides an intuitive and interactive user interface for word prediction.
- **Custom Sequence Handling**: Handles varying lengths of text inputs with padding for consistent predictions.

---

## **How It Works**

1. **Model**: The project uses a trained LSTM model (`next_word_lstm.h5`) to predict the next word.
2. **Tokenizer**: A pre-trained tokenizer (`tokenizer.pickle`) converts text into sequences that can be fed into the model.
3. **Prediction**: The application takes user input, processes it, and predicts the next word using the LSTM model.
4. **Interactive UI**: The application is built using Streamlit, allowing users to interact seamlessly with the prediction system.

---

## **Technologies Used**

- **Python**: Core programming language.
- **TensorFlow/Keras**: For building and training the LSTM model.
- **Streamlit**: For developing the user-friendly web interface.
- **Numpy**: For numerical computations.
- **Pickle**: For saving and loading the tokenizer.

---

## **Setup Instructions**

1. **Clone the Repository**
   ```bash
   git clone https://github.com/unbeatablekd/Next-Word-Prediction.git
   cd Next-Word-Prediction
   ```

2. **Create and Activate a Virtual Environment**
   ```bash
   python -m venv myenv
   source myenv/bin/activate    # For Linux/Mac
   myenv\Scripts\activate       # For Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   streamlit run app.py
   ```

5. **Interact with the Application**
   - Enter a sequence of words in the input field.
   - Click the "Predict Next Word" button to see the prediction.

---

## **Example**

Input:  
`"To be or not to be"`

Output:  
`"continued"`

---

## **Folder Structure**

```
Next-Word-Prediction/
│
├── app.py                    # Streamlit application file
├── next_word_lstm.h5         # Trained LSTM model
├── tokenizer.pickle          # Tokenizer for processing text
├── requirements.txt          # Project dependencies
├── README.md                 # Project documentation
└── myenv/                    # Virtual environment folder (not included in GitHub)
```

---

## **Future Improvements**

- Train the LSTM model on a larger and more diverse dataset for better accuracy.
- Add support for predicting multiple possible next words with confidence scores.
- Enhance the user interface with additional customization options.
- Extend functionality to support multi-word predictions.

---

## **Contributors**

- [**Kaushik**](https://github.com/unbeatablekd) - Developer

---
