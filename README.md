# WhatsApp-Chat-Analyser
# 📱 WhatsApp Chat Analyzer

An interactive tool to analyze WhatsApp chat data and extract insights such as message frequency, active hours, and top contacts using Python. The tool helps visualize chat patterns and provides detailed statistics.

---

## 📌 Objective

To analyze and visualize WhatsApp chat data by:
- Extracting key statistics such as word count, message frequency, and sentiment analysis.
- Identifying the most frequent contacts and best time to chat.
- Visualizing chat activity over time.

---

## 🧰 Tools & Technologies

- **Programming Language**: Python
- **Libraries**:
  - `pandas` – for data manipulation
  - `matplotlib`, `seaborn` – for data visualization
  - `nltk` – for text processing and sentiment analysis
- **Environment**: Jupyter Notebook

---

## 📁 Dataset

- **Source**: Exported WhatsApp chat from your phone (export as `.txt`).
- **Features**:
  - `Date` – Date and time of the message
  - `Sender` – Sender of the message
  - `Message` – Text content of the message

---

## 🧠 Key Steps

1. **Data Preprocessing**:
   - Clean and format the raw chat data
   - Handle emojis, URLs, and special characters

2. **Exploratory Data Analysis (EDA)**:
   - Calculate message frequency over time
   - Identify the most frequent contacts
   - Perform sentiment analysis on messages

3. **Data Visualization**:
   - Visualize daily/weekly message counts
   - Display word clouds for the most common words
   - Graph top contacts based on message count

---

## 📈 Insights & Results

- 📅 **Most Active Day**: Day X with Y messages
- 🕒 **Best Time to Chat**: Around H:00 PM
- 🧑‍🤝‍🧑 **Top Contact**: Contact Z with N messages
- 💬 **Sentiment Analysis**: Predominantly positive/neutral/negative messages

---

## 🚀 Getting Started

### 📦 Install Requirements

```bash
pip install pandas matplotlib seaborn nltk
