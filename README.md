# 🧠 Synthetic Personality Analysis – Introverts vs Extroverts

This project explores the behavioral differences between **introverts** and **extroverts** using a synthetic dataset powered by [Syncora.ai](https://syncora.ai). The interactive Power BI dashboard visualizes patterns in social behavior, emotional energy, and personality-linked preferences.

## 📊 Project Overview

As personality traits influence how people engage with others, spend time alone, and use social platforms, this dashboard investigates:

- Time spent alone
- Stage fear (stage fright)
- Social media post frequency
- Number of social events attended
- Energy levels after socializing
- Frequency of going outside
- Friends circle size

The dashboard segments users by **introvert** and **extrovert** types to discover:
- Who prefers solitude
- Who posts more on social media
- Who feels drained after events
- And more!

> ⚠️ This is **synthetic data** – no real individuals are represented. Generated for ethical experimentation and learning.

## 📁 Dataset Information

**Source**: Synthetic Personality Dataset by Syncora.ai  
**Records**: 10,000  
**Format**: CSV  
**Target Variable**: `Personality` (0 = Extrovert, 1 = Introvert)

### 🧾 Features

| Column                     | Description                                      |
|---------------------------|--------------------------------------------------|
| Time_spent_Alone          | Daily hours spent alone (0–11)                   |
| Stage_fear                | Stage fright (0 = No, 1 = Yes)                   |
| Social_event_attendance   | Weekly events attended (0–10)                    |
| Going_outside             | Outdoor frequency per week (0–7)                 |
| Drained_after_socializing | Energy loss after socializing (0 = No, 1 = Yes) |
| Friends_circle_size       | No. of close friends (0–15)                      |
| Post_frequency            | Weekly social media posts (0–10)                |
| Personality               | Personality label (0 = Extrovert, 1 = Introvert)|

## 📈 Power BI Dashboard

### ✅ Key Features

- **KPI Cards**: Total records, average time spent alone
- **Bar Charts**: Distribution of time alone, post frequency, stage fear
- **Scatter Plot**: Relationship between going outside vs social events
- **Treemap**: Event attendance by post frequency and personality
- **Pie Chart**: Distribution by friends circle size
- **Slicers**: Filter views by personality type and stage fear

![Dashboard Screenshot](./Introvert%20and%20extrovert.PNG)

## 🧰 Tools Used

| Tool        | Purpose                                  |
|-------------|------------------------------------------|
| Power BI    | Data visualization & dashboard design    |
| Excel       | Basic data preprocessing                 |
| GitHub      | Version control & project showcase       |

## 🚀 How to Use

1. Clone or download the repository.
2. Open the `.xlsx` file to preview the raw data.
3. Open the Power BI file (`.pbix`) if shared (or rebuild visuals using screenshots).
4. Explore patterns using slicers and visuals.

## 📎 Repository Structure

```
📁 root/
├── introvert and extrovert.xlsx       # Original dataset
├── Introvert and extrovert.PNG        # Dashboard screenshot
└── README.md                          # Project overview
```

## 🙌 Acknowledgements

- **Syncora.ai** for the privacy-safe synthetic dataset  
- **Microsoft Power BI** for enabling effective storytelling through data  
- **OdinSchool** for guidance on analytics fundamentals  

## 👨‍💻 Author

**Chanu041**  
📬 Connect with me on [LinkedIn]((https://www.linkedin.com/in/chan-basha-shaik-20b049228/))  
🔗 Explore more projects at: [https://github.com/Chanu041](https://github.com/Chanu041)

## 📌 License

This project is open for educational, experimental, and analytical use only.  
**No commercial use of synthetic data permitted.**

> "Explore personality. Model behavior. Build ethically."
