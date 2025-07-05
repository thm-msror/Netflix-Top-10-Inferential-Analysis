# 🎬 Netflix Top 10 Inferential Analysis

This project explores how **content genres** and **IMDb ratings** impact the **popularity and longevity** of Netflix titles in the Global Top 10 chart using inferential statistics.

---

## 📌 Objective

- Determine if some genres lead to longer popularity on Netflix (Chi-Square)
- Analyze whether IMDb ratings vary across genres (ANOVA)
- Predict how long a title will stay popular using genre and rating (Regression)

---

## 🗂️ Repository Structure

<pre><code> 
Netflix-Inferential-Analysis/
│
├── Datasets/
│   ├── most_popular_global_alltime.csv             # Raw Netflix weekly Top 10 data
│   ├── omdb_results.csv                            # Raw metadata from OMDb API
│   ├── final_netflix_omdb_dataset_cleaned.csv      # Cleaned + merged dataset
│   └── netflix_omdb_dataset.csv                    # Final version used in notebook
│
├── final_dataset_preparation.ipynb                 # Data cleaning and merging
├── Netflix_Inferential_Analysis.ipynb              # Main inferential analysis
├── Project_NetflixContentAnalysis.pbix             # Power BI Dashboard
├── ProjectPPT_NetflixContentAnalysis.pdf           # Presentation slides
├── README.md
└── LICENSE

</code></pre>

---

## 📊 Tools Used

- **Python** (Pandas, Seaborn, StatsModels, SciPy)
- **Power BI** for dashboard and storytelling
- **OMDb API** for metadata enrichment

---

## 🔬 Statistical Tests Performed

| Test        | Purpose                                                        |
|-------------|----------------------------------------------------------------|
| Chi-Square  | Check if genre affects popularity band                         |
| ANOVA       | Check if IMDb ratings vary significantly by genre             |
| Regression  | Predict title longevity using genre tags and IMDb rating      |

---

## 📁 Key Files

| File                                      | Description                            |
|-------------------------------------------|----------------------------------------|
| `final_dataset_preparation.ipynb`         | Cleaning + merging Netflix & OMDb data |
| `Netflix_Inferential_Analysis.ipynb`      | Chi-Square, ANOVA, Regression analysis |
| `Project_NetflixContentAnalysis.pbix`     | Power BI dashboard                     |
| `ProjectPPT_NetflixContentAnalysis.pdf`   | Summary slides for presentation        |

---

## 🧠 Insights Summary

- **Genres are linked to popular bands** (Chi-Square)
- **Audience ratings differ by genre** (ANOVA)
- **Genre tags + IMDb ratings help predict longevity** (Regression)

---

## 📽️ Business Impact

Netflix can:

- Prioritize genres that sustain Top 10 performance
- Improve content investment decisions
- Estimate show longevity before launch

---

## 👩‍💻 Author

**Tehreem Masroor**  
DSAI3301 – Data Analysis & Visualization  
University of Doha for Science & Technology

---

## 📜 License

This project is licensed under the MIT License.
