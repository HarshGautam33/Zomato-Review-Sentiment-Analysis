# 🍽️ Zomato Restaurant Reviews - Sentiment Analysis & Topic Modeling (Hyderabad, India)

This project focuses on performing **sentiment analysis** and **topic modeling** on restaurant reviews from **Zomato** in **Hyderabad, India**. The objective is to extract actionable insights from customer feedback to understand how diners feel about restaurants and what topics or themes dominate their reviews.

---

## 📚 Table of Contents

* [Project Overview](#project-overview)
* [Data Description](#data-description)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Outputs](#outputs)
* [Technologies Used](#technologies-used)
* [Contributions](#contributions)
* [License](#license)

---

## 📌 Project Overview

The primary goals of this project are:

* 💡 Conduct **Exploratory Data Analysis (EDA)** to understand the data distribution and identify key patterns.
* 😃 Perform **Sentiment Analysis** using NLP techniques to classify reviews into **positive**, **neutral**, and **negative** categories.
* 🧠 Apply **Topic Modeling** using **Latent Dirichlet Allocation (LDA)** to uncover the main themes discussed by customers.
* 📈 Provide visual insights and metrics to support business decisions for restaurants.

This analysis can help restaurant owners, food enthusiasts, and data scientists better understand customer preferences and areas of improvement.

---

## 📊 Data Description

The dataset used in this project includes restaurant-level and review-level features from Zomato listings in Hyderabad. Below are the primary columns:

| Column Name   | Description                                                            |
| ------------- | ---------------------------------------------------------------------- |
| `Name`        | Name of the restaurant                                                 |
| `Links`       | Direct link to the restaurant on Zomato                                |
| `Cost`        | Average cost for two people                                            |
| `Collections` | Zomato collection tags (e.g., Romantic, Buffet)                        |
| `Cuisines`    | Types of cuisines offered (e.g., Chinese, South Indian)                |
| `Timings`     | Restaurant opening and closing hours                                   |
| `Reviews`     | Customer-written textual reviews (used for sentiment & topic modeling) |

---

## ⚙️ Installation

To set up this project locally:

1. **Clone the repository:**

```bash
git clone https://github.com/Swaran2003/zomato-sentiment-analysis.git
```

2. **Navigate to the project directory:**

```bash
cd zomato-sentiment-analysis
```

3. **Create a virtual environment (optional but recommended):**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

4. **Install required dependencies:**

```bash
pip install -r requirements.txt
```

---

## 🧪 Usage

To run the complete analysis:

1. Launch **Jupyter Notebook**:

```bash
jupyter notebook
```

2. Open the notebook:

```
zomato-reviews-sentiment-analysis.ipynb
```

3. Follow the code cells to:

   * Load the dataset
   * Conduct EDA
   * Perform Sentiment Analysis using tools like TextBlob/VADER
   * Perform Topic Modeling using LDA
   * Visualize and interpret results

---

## 📂 Project Structure

```
├── data/
│   └── zomato_reviews.csv
├── outputs/
│   ├── sentiment_plots.png
│   ├── lda_topics.html
├── zomato-reviews-sentiment-analysis.ipynb
├── requirements.txt
├── README.md
```

---

## 📊 Outputs

* **Sentiment Distribution**: Pie/Bar charts showing proportion of positive, neutral, and negative reviews.
* **Word Clouds**: Top words for each sentiment category.
* **LDA Topics**: Interactive visualizations of discovered topics.
* **Insights**: Notable trends and frequent customer concerns or praises.

---

## 🚀 Technologies Used

* **Python**
* **Pandas, NumPy** – data manipulation
* **NLTK, TextBlob, VADER** – sentiment analysis
* **Gensim, sklearn** – topic modeling
* **Matplotlib, Seaborn, Plotly, pyLDAvis** – visualizations
* **Jupyter Notebook** – interactive development

---

## 🛠️ Contributions

Contributions are welcome! If you'd like to:

* Suggest a new feature
* Report a bug
* Add new visualizations or extend the analysis

Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
