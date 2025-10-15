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
## Visual Analytics 

## Normalized_used_price:
<img width="1826" height="825" alt="image" src="https://github.com/user-attachments/assets/ba4f669a-055c-433a-9942-314c1b8b8e1a" />
## Normalized new price 
<img width="1735" height="797" alt="image" src="https://github.com/user-attachments/assets/ead241cf-f25c-4a95-aa5c-4b80b1a6a2cd" />
## Screen_size :
<img width="1857" height="816" alt="image" src="https://github.com/user-attachments/assets/84750783-8f78-4e67-8f6b-0a55dc42ac8b" />
## main_camera_mp: 
<img width="1847" height="798" alt="image" src="https://github.com/user-attachments/assets/7953b27d-a28f-4ae8-b017-1f515d6e78d2" />
## selfie_camera_mp :
<img width="1793" height="818" alt="image" src="https://github.com/user-attachments/assets/909d6fb4-93d2-493b-a62b-71552bdd609c" />
## int_memory :
<img width="1702" height="808" alt="image" src="https://github.com/user-attachments/assets/3da67c0a-aa03-4912-a5c6-9a2a9273e252" />
## ram:
<img width="1743" height="818" alt="image" src="https://github.com/user-attachments/assets/e122ad23-393b-4914-863b-6de69cd754ef" />
## weight 
<img width="1711" height="817" alt="image" src="https://github.com/user-attachments/assets/e4b8e2fe-cf7c-482c-977f-efeb100acd91" />
## battery 
<img width="1743" height="812" alt="image" src="https://github.com/user-attachments/assets/139de32d-426e-4edf-9524-10b173decd84" />
## days_used 
<img width="1647" height="801" alt="image" src="https://github.com/user-attachments/assets/0ddde6c5-fb75-4cc8-99d2-34a5729b0b26" />
## brand_name :
<img width="1447" height="822" alt="image" src="https://github.com/user-attachments/assets/72337723-0c6f-4caa-8035-30ddbca58edb" />
<img width="1470" height="812" alt="image" src="https://github.com/user-attachments/assets/31320adc-64f3-4e3e-8ce7-2136106b3095" />
<img width="1440" height="731" alt="image" src="https://github.com/user-attachments/assets/c1a2d0e2-f9b9-4f30-ada2-3a7a94967c5b" />
<img width="1455" height="732" alt="image" src="https://github.com/user-attachments/assets/d27c82c0-d99e-48ae-8a2f-2d32c6503281" />
<img width="1427" height="768" alt="image" src="https://github.com/user-attachments/assets/b9575c47-5667-4d9f-9696-8fd830c6953c" />

## heat map
<img width="1796" height="853" alt="image" src="https://github.com/user-attachments/assets/0de265b6-cc04-4fe6-85b7-04ccfa2934c7" />
<img width="1785" height="467" alt="image" src="https://github.com/user-attachments/assets/c097b339-6f16-47ad-b14d-7dd83871130a" />

## box-plot
<img width="1682" height="840" alt="image" src="https://github.com/user-attachments/assets/84aeda62-a977-4eb7-b244-80501ea1e14f" />
<img width="1692" height="637" alt="image" src="https://github.com/user-attachments/assets/c800ae45-4f9d-4cdc-9708-37304b128065" />
## brand name 
<img width="1827" height="832" alt="image" src="https://github.com/user-attachments/assets/7901845e-875b-45ee-b1f4-44dac8aa3a33" />
<img width="1593" height="818" alt="image" src="https://github.com/user-attachments/assets/f61543cd-0ac3-4959-9b90-82ab56a4c798" />
<img width="1611" height="843" alt="image" src="https://github.com/user-attachments/assets/c3d9bd58-e35b-4b12-8fd8-ebebb36d60fa" />
## line plot 
<img width="1293" height="611" alt="image" src="https://github.com/user-attachments/assets/21761025-b536-458a-884d-57208dc0ad12" />
<img width="1186" height="530" alt="image" src="https://github.com/user-attachments/assets/1595554b-b6ee-458b-9e98-c47a4545955e" />

## linear regresion 

<img width="947" height="645" alt="image" src="https://github.com/user-attachments/assets/f595a904-0c59-478c-9ec8-8910ec514584" />
<img width="895" height="627" alt="image" src="https://github.com/user-attachments/assets/df0a926c-0100-4333-97d3-7389d9b0e052" />


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
