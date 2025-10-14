# 📱 ReCell - Dynamic Pricing Model for Used Phones & Tablets

![ReCell Banner](https://images.unsplash.com/photo-1512499617640-c2f99909808d?auto=format&fit=crop&w=1350&q=80)

---

## 🚀 Project Overview

The global market for used and refurbished phones and tablets is booming, predicted to reach **$52.7 billion by 2023** with a CAGR of 13.6%! 🌍💰

ReCell is a startup tapping into this growing opportunity by developing a **machine learning-based dynamic pricing model** to accurately predict the resale value of used devices. This helps optimize buying and selling strategies for both the company and consumers.

---

## 🎯 Objective

- Build a **linear regression model** to **predict the normalized resale price** of used phones/tablets.
- Identify key **factors that influence the resale price**.
- Provide **actionable insights and recommendations** to guide inventory and pricing strategy.

---

## 📊 Data Description

| Feature               | Description                                  |
|-----------------------|----------------------------------------------|
| `brand_name`          | Manufacturer brand (e.g., Apple, Samsung)    |
| `os`                  | Operating system (Android, iOS, etc.)        |
| `screen_size`         | Screen size (cm)                              |
| `4g`                  | 4G support (0/1)                             |
| `5g`                  | 5G support (0/1)                             |
| `main_camera_mp`      | Rear camera resolution (megapixels)          |
| `selfie_camera_mp`    | Front camera resolution (megapixels)         |
| `int_memory`          | Internal memory (GB)                          |
| `ram`                 | RAM size (GB)                                |
| `battery`             | Battery capacity (mAh)                        |
| `weight`              | Device weight (grams)                         |
| `release_year`        | Year of device release                        |
| `days_used`           | Number of days device has been used           |
| `normalized_new_price`| Normalized price of new device (€)            |
| `normalized_used_price`| Normalized price of used device (€) - Target |

---

## 🧠 Methodology

1. **Data preprocessing**: Handle missing data, encode categorical variables, and scale numerical features.
2. **Exploratory Data Analysis (EDA)**: Understand distributions and relationships.
3. **Linear Regression Modeling**:
   - Train/test split.
   - Model fitting and evaluation.
4. **Model Interpretation**: Analyze coefficients to find significant price drivers.
5. **Recommendations**: Translate insights into actionable business strategies.

---

## 📈 Key Findings

| Insight                                         | Impact/Effect                                  |
|------------------------------------------------|-----------------------------------------------|
| Model explains ~83% variance                    | Strong predictive power                        |
| Each year since release reduces price by ~2.9% | Device depreciation over time                  |
| Higher `normalized_new_price` → higher resale  | Premium devices retain value                   |
| Higher camera megapixels increase resale price | Buyers value camera quality                     |
| More RAM increases resale price                 | Performance specs matter                        |
| Heavier devices have slightly higher prices    | Possible link to battery/build quality         |
| Brand effects: Karbonn (+0.1156), Xiaomi (+0.08)| Preferred brands for resale                      |
| Brand effects: Samsung (-0.0374), Sony (-0.067) | Brands to avoid focusing on                     |
| 4G support increases price by ~5%               | 4G devices more valued currently                |
| 5G support surprisingly lowers resale price     | Possibly market adoption lag or pricing factors |

---

## 📝 Recommendations for ReCell

- 🎯 **Focus on high-end, premium devices** to maximize resale value.
- ⏳ Target devices **released within last 12-18 months**.
- 📸 Prioritize devices with **high camera quality** (main & selfie cameras).
- 💾 Ensure devices have **higher RAM and storage**.
- ⚖️ Include **heavier devices** due to build/battery quality appeal.
- 🏷️ Favor **Karbonn and Xiaomi** brands; avoid Samsung and Sony.
- 📡 Focus on **4G devices** for now; be cautious with 5G models.

---

## 💻 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ReCell-Dynamic-Pricing.git
2. Navigate to the project directory:
   cd ReCell-Dynamic-Pricing
3.Install dependencies:
pip install -r requirements.txt
4.Run the notebook or script to train the model and generate results.

📬 Contact & Contributions

Contributions are welcome! Feel free to open issues or submit pull requests.
For questions or collaborations, contact: vasupriya2000@gmail.com

🤝 Acknowledgments

Data inspired by IDC forecasts and market analysis reports

Thanks to open-source tools: scikit-learn, pandas, matplotlib, seaborn

⭐️ If this project helped you, please star the repository!
<p align="center"> <img src="https://media.giphy.com/media/3ohhwytHcusSCXXOUg/giphy.gif" alt="Thank You" width="300"/> </p> ```
