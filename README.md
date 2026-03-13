# 📊 Social Media Sentiment & Engagement Analysis

A modular Python pipeline for loading, cleaning, and visualising social media engagement data across platforms, post types, and time periods.

---

## 📁 Project Structure

```
socialmedia_sentiment_engagement_analysis_machine_learning/
├── src/
│   ├── analysis.py                    # Optimized modular pipeline
│   └── socialmediadataanalysis.py     # Original notebook reference
├── assets/                            # Chart images
├── requirements.txt
├── .gitignore
└── README.md
```

---

## 🚀 Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/dipanburja/socialmedia_sentiment_engagement_analysis_machine_learning.git
cd socialmedia_sentiment_engagement_analysis_machine_learning
```

### 2. Create a virtual environment
```bash
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the pipeline
```bash
python src/analysis.py social_media_engagement.csv
```

---

## 📊 Sample Output Charts

### 🏆 Executive Dashboard — All Summary Report
![All Summary Report](assets/all_summary_report.png)

### 🌐 Average Engagement by Platform
![Average Like Per Platform](assets/average_like_per_platform.png)

### 📅 Average Engagement by Day and Platform
![Average Engagement Day and Platform](assets/average_engagement_day_and_platform.png)

### 💬 Average Engagement by Sentiment Type
![Average Engagement For Sentiment Type](assets/average_engagement_for_sentiment_type.png)

### 🥧 Contribution of Post Types (by Engagement)
![Contribution of Post Type Engagement](assets/contribution_of_posttype_engagement.png)

### 🥧 Contribution of Post Types (by Volume)
![Contribution of Post Type](assets/contribution_of_posttype.png)

### 🔗 Correlation Between Post Engagement
![Correlation Between Post Engagement](assets/corelation_between_post_engagement.png)

### 📈 Engagement Trend Over Month
![Engagement Trend Over Month](assets/enagement_trend_over_month.png)

### 📆 Number of Posts Per Day
![Number of Posts Per Day](assets/number_post_per_day.png)

### 📦 Engagement Distribution by Post Type
![Post Type](assets/post_type.png)

### 🕐 Volume of Posts vs. Average Engagement by Hour
![Volume of Posts Per Hour](assets/volumn_of_post_per_hour.png)

---

## 📦 Dataset Format

| Column | Type | Description |
|---|---|---|
| `post_id` | string/int | Unique post identifier |
| `platform` | string | e.g. `Facebook`, `Instagram`, `Twitter` |
| `post_type` | string | e.g. `image`, `video`, `text`, `carousel`, `poll` |
| `post_day` | string | Day name, e.g. `Monday` |
| `post_time` | datetime | Full timestamp |
| `likes` | int | Like count |
| `comments` | int | Comment count |
| `shares` | int | Share count |
| `sentiment_score` | string | `positive`, `neutral`, or `negative` |

---

## 🔑 Key Findings

- **Instagram** drives the highest average engagement (42.2%)
- **Polls and videos** outperform other post types
- **1 AM and 9 PM** are peak engagement hours
- **Negative sentiment** posts receive slightly higher engagement than positive ones
- **Wednesday and Friday** generate the most total interactions
- **Likes** have a very strong correlation (0.98) with overall engagement

---

## 🛠 Tech Stack

- **pandas** – data wrangling
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – visualisation
- **scikit-learn** – ML extensions

---

## 📄 License

MIT License — feel free to use, modify, and share.