#  Spam Email Classification with BOW

This project demonstrates the process of classifying spam emails using various Natural Language Processing (NLP) techniques in Python. The dataset used contains both spam and ham (non-spam) emails, and the project follows steps to normalize the text, remove punctuation and stop words, and apply the Bag of Words (BOW) technique to analyze word frequencies.

## Features

- Data cleaning and preprocessing (lowercasing, stop word removal, etc.)
- Bag of Words (BOW) model to calculate word frequency
- Visualization of spam and ham distribution
- Identification of the most common words in spam emails

## Steps Involved

1. **Dataset loading**: A CSV file of emails is loaded and examined.
2. **Data preprocessing**:
    - Convert text to lowercase.
    - Remove punctuation and stop words.
3. **Bag of Words (BOW)**:
    - Applying the BOW technique to count the frequency of words in spam emails.
    - Identify the most frequently used words in the spam email dataset.
4. **Visualization**:
    - Pie chart displaying the distribution of spam vs. ham emails.
  
## Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `sklearn`

## Dataset

The dataset consists of 5728 emails with two columns:
- **text**: The content of the email.
- **spam**: A binary label where 1 indicates a spam email and 0 indicates a ham email.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/spam-email-classification-bow.git
    cd spam-email-classification-bow
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the notebook:
    Open the `DH_task2.ipynb` notebook and execute the cells in order.

## Results

The BOW model identifies the top 20 most common words in spam emails, helping to understand patterns in spam detection.

## License

This project is licensed under the MIT License.
