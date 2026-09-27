# My Data Science Journey & Study Reference

A structured, web-based study reference hub built from hands-on Jupyter Notebooks, original research notes, and core mathematics & statistics foundations. Covers **Python Core**, **NumPy**, **Pandas**, **Data Manipulation**, **Data Visualization** (Matplotlib & Seaborn), **SQL (SQLite)**, **Flask**, **Streamlit**, and **Descriptive Statistics** — all with tested code examples and detailed explanations in Bengali.

## 🌐 Live Website

Access the interactive study reference dashboard online:
👉 **[Live Study Reference Hub](https://adnan-eram-argho.github.io/My-Data_science_journey/)**

---

## 📚 Project Structure

```
Website-root/
├── index.html              ← Landing page & Quick Topic Index (94 topics)
├── style.css               ← Shared dark-mode design system
├── .nojekyll               ← GitHub Pages static site config
├── python/
│   └── index.html          ← Python Core (23 topics)
├── numpy/
│   └── index.html          ← NumPy + Pandas + Data Manipulation + Visualization (47 topics)
├── sql/
│   └── index.html          ← SQL / SQLite via Python (7 topics)
├── flask/
│   └── index.html          ← Flask Web Development (5 topics)
├── streamlit/
│   └── index.html          ← Streamlit Data Apps (2 topics)
└── statistics/
    └── index.html          ← Descriptive Statistics (10 topics) ← NEW
```

---

## 📦 Active Modules

### 🐍 Python Core & Functional Tools
> `python/index.html` · **23 topics** · **60+ code cells**

| # | Topic | # | Topic |
|---|---|---|---|
| 01 | Lists | 13 | Exception Handling |
| 02 | Tuples | 14 | Magic Methods |
| 03 | Dictionaries | 15 | OOP Basics |
| 04 | Sets | 16 | Encapsulation |
| 05 | Functions | 17 | Inheritance |
| 06 | Lambda Functions | 18 | Polymorphism |
| 07 | map() | 19 | Abstraction |
| 08 | filter() | 20 | Custom Exceptions |
| 09 | Comparison | 21 | Iterators |
| 10 | Modules & Packages | 22 | Generators |
| 11 | Standard Library | 23 | Decorators |
| 12 | File Operations | | |

---

### 🔢 NumPy & Data Analytics
> `numpy/index.html` · **47 topics** · **85+ code cells**

#### NumPy (16 topics)
| # | Topic | # | Topic |
|---|---|---|---|
| 01 | 1D & 2D Arrays | 09 | Normalization |
| 02 | Special Arrays | 10 | Boolean Indexing |
| 03 | Array Attributes | 11 | Random Numbers |
| 04 | Vectorized Operations | 12 | Advanced Indexing |
| 05 | Universal Functions | 13 | Axis-wise Operations |
| 06 | Indexing & Slicing | 14 | Broadcasting |
| 07 | Array Modify | 15 | Linear Algebra |
| 08 | Statistical Functions | 16 | Structured & Masked Arrays |

#### Pandas (4 topics)
| # | Topic |
|---|---|
| 01 | Series |
| 02 | DataFrame |
| 03 | Row & Element Access |
| 04 | Add, Drop & Modify |

#### Data Manipulation (10 topics)
| # | Topic | # | Topic |
|---|---|---|---|
| 01 | Data Overview | 06 | Merge & Concat |
| 02 | Missing Values | 07 | Pivot Table |
| 03 | Rename & Dtypes | 08 | MultiIndex DataFrame |
| 04 | apply() & Lambda | 09 | Time Series Basics |
| 05 | GroupBy & Aggregation | 10 | Text/String Operations |

#### Read & Write (3 topics)
| # | Topic |
|---|---|
| 01 | CSV Files |
| 02 | JSON Read & Write |
| 03 | HTML Table Read |

#### Matplotlib (6 topics)
| # | Topic | # | Topic |
|---|---|---|---|
| 01 | Line Plot | 04 | Histogram |
| 02 | Multiple Subplots | 05 | Scatter Plot |
| 03 | Bar Plot | 06 | Pie Chart |

#### Seaborn (8 topics)
| # | Topic | # | Topic |
|---|---|---|---|
| 01 | Dataset Load | 05 | Box & Violin Plot |
| 02 | Scatter Plot | 06 | Histogram & KDE |
| 03 | Line Plot | 07 | Pair Plot |
| 04 | Bar Plot | 08 | Heatmap |

---

### 🗄️ SQL (SQLite) via Python
> `sql/index.html` · **7 topics** · **16 code cells**

| # | Topic | Description |
|---|---|---|
| 01 | Connection & Cursor | `sqlite3.connect()`, cursor creation |
| 02 | Create Table | `CREATE TABLE IF NOT EXISTS`, constraints |
| 03 | INSERT | Single inserts & `executemany` with `?` placeholders |
| 04 | SELECT & fetchall | Querying rows, `fetchall()` vs `fetchone()` |
| 05 | UPDATE & DELETE | Modifying/removing rows with `WHERE` |
| 06 | DROP TABLE & Close | Removing tables, closing connections |
| 07 | Full Example: Sales | End-to-end CRUD workflow with sales data |

---

### 🌶️ Flask Web Development
> `flask/index.html` · **5 topics** · **20+ code cells**

| # | Topic |
|---|---|
| 01 | Flask Basics & Routing |
| 02 | Templates & render_template() |
| 03 | GET & POST Requests |
| 04 | Jinja2 Templating Deep Dive |
| 05 | Building a REST API |

---

### 🎈 Streamlit Data Apps
> `streamlit/index.html` · **2 topics** · **7+ code cells**

| # | Topic |
|---|---|
| 01 | Display Elements & Charts |
| 02 | Interactive Widgets & File Upload |

---

### 📊 Descriptive Statistics ← NEW
> `statistics/index.html` · **10 topics** · **20+ formulae** · **সম্পূর্ণ বাংলা**

| # | Topic | Key Concepts |
|---|---|---|
| 01 | Statistics কী | Descriptive vs Inferential — সংজ্ঞা ও পার্থক্য |
| 02 | Central Tendency | Mean (μ, x̄), Median (position formula), Mode |
| 03 | Variance & SD | Population/Sample সূত্র, Bessel's Correction (n−1) |
| 04 | Variable প্রকারভেদ | Qualitative/Quantitative, Nominal/Ordinal/Interval/Ratio |
| 05 | Random Variable | Discrete vs Continuous, PMF vs PDF |
| 06 | Histogram | সংজ্ঞা, Bar Chart থেকে পার্থক্য, inline SVG chart |
| 07 | Percentile & Quartile | Position সূত্র, interpolation পদ্ধতি, Q1/Q2/Q3 |
| 08 | 5 Number Summary & Box Plot | IQR, Fence Value, outlier detection, inline SVG |
| 09 | Covariance | Population/Sample সূত্র, Cov(X,X) = Var, advantages/disadvantages |
| 10 | Correlation | Pearson (r) ও Spearman (ρ) — দুটি সমতুল্য সূত্র সহ |

> **Note:** কাঠামো এমন রাখা হয়েছে যাতে পরে **Inferential Statistics** একই `index.html`-এ সহজে যোগ করা যায়।

---

## 🚀 Features

- **94 Topics** across 6 active modules with **180+ tested code examples**
- **Consolidated Notebooks**: Multiple Jupyter notebooks integrated into single, searchable web pages
- **Quick Topic Index**: Jump to any topic across all modules from the homepage
- **Inline SVG Visualizations**: Histogram, Box Plot, Scatter Plot, Variable hierarchy diagram, Correlation scale — all embedded as responsive SVG
- **Dual-language Content**: Technical terms in English, detailed explanations in Bengali (বাংলা)
- **Mathematical Formulae**: Every formula verified and presented with numeric examples
- **Detailed Nuances**: Syntax explanations, edge-case warnings (⚠), tips (💡), and notes (📝)
- **Original Code Preserved**: All comments from original notebooks kept intact
- **Modern Dark UI**: JetBrains Mono code font, responsive grid layout, sidebar navigation with scroll-highlight
- **Mobile Responsive**: Collapsible sidebar with toggle, stacked cards on small screens
- **Slot-comment Workflow**: `<!-- SLOT:NAV -->` and `<!-- SLOT:SECTION -->` markers for easy content expansion

---

## 🛠️ Tech Stack

| Component | Technology |
|---|---|
| Structure | HTML5 (semantic) |
| Styling | Vanilla CSS (custom dark theme) |
| Charts | Inline SVG (no external library) |
| Fonts | Google Fonts — Inter + JetBrains Mono |
| Hosting | GitHub Pages |
| Source | Jupyter Notebooks + Study Notes |

---

## 📌 Planned Modules

- 🤖 **Machine Learning** — Scikit-Learn, Regression, Classification, Model Tuning
- 📈 **Inferential Statistics** — Hypothesis Testing, Confidence Intervals, p-value, Distributions

---

## 👤 Author

**Adnan Eram Argho**
- GitHub: [@Adnan-Eram-Argho](https://github.com/Adnan-Eram-Argho)
- Course: Krish Naik's Complete Data Science Bootcamp (Udemy)
