# 🖥️ T03: TV Energy Consumption Data Visualization

## 📖 Data Story

### 🎯 Target Audience

Our visualisation is designed for **consumers and policymakers** interested in understanding television energy consumption trends in Australia.

**Primary Audience:**

* Environmentally conscious consumers purchasing new TVs
* General users comparing energy efficiency and running costs

**Secondary Audience:**

* Sustainability and energy agencies developing efficiency programs
* Retailers and technology analysts examining market trends

**Audience Characteristics:**

* Prefer clear, visual explanations over technical details
* Interested in actionable insights (e.g., “Which TV type uses the least power?”)
* Expect data-driven, factual information that can influence purchase or policy decisions

---

### 💡 Audience Interest

Our audience wants to:

1. Identify which **TV screen technologies** are most common and efficient
2. Understand **which screen sizes** are most popular in the Australian market
3. Discover **which brands** offer the most TV models and market dominance
4. Learn **which screen types use the least energy**
5. Explore the **relationship between screen size, power usage, and star ratings**
6. Apply these insights to **make informed and sustainable choices**

---

## 🎨 Visualization Guidelines

To ensure clarity and accessibility, the following principles were applied throughout the design process:

1. **Clarity:** Use clean, consistent color schemes (colorblind-friendly blues and oranges).
2. **Context:** Each visual includes labels and captions explaining what the data shows.
3. **Comparisons:** Multiple chart types (pie, bar, scatter) are used for side-by-side interpretation.
4. **Narrative Flow:** The visuals follow a logical order — from market overview to detailed performance insights.
5. **Accessibility:** Visuals use simple legends, descriptive titles, and alt text for inclusivity.
6. **Actionable Insights:** Each chart answers a question relevant to the audience (e.g., “Which TV size is most efficient?”).

---

## 📊 About the Data

### 🗂️ Data Source

Data was obtained from the **Australian Government’s Appliance Energy Consumption Database (2020–2024)**, which includes detailed information on registered television models, screen technologies, energy ratings, and power usage.

---

### ⚙️ Data Processing

Data was:

* Cleaned and filtered in **KNIME** to remove missing or duplicate entries
* Categorised by **screen technology**, **brand**, and **screen size**
* Aggregated to calculate **average power consumption**, **frequency counts**, and **energy star ratings**
* Exported for visualisation using web-based tools (HTML, CSS, JS, and D3.js)

---

### 🔒 Privacy

The dataset contains **no personally identifiable information**. All data represents product-level records published by the Australian Government for public educational and research purposes.

---

### 📏 Accuracy and Limitations

* Measurements are based on manufacturer-provided data and official testing standards.
* Market coverage may not include discontinued or unregistered models.
* Energy efficiency may vary slightly in real-world use due to user settings and display modes.
* Star ratings and wattage are accurate within the range provided by official testing.

---

### ⚖️ Ethics

* Data is used solely for **educational and sustainability-awareness** purposes.
* Visualisations are designed to **inform**, not promote or criticise specific brands.
* Interpretation avoids bias and presents both positive and negative efficiency trends.

---

## 🧠 Key Insights from Visualisations

1. **Screen Technology Distribution:**
   LCD (LED) is the most common technology, followed by OLED.
   → Consumers have the widest choice in LED TVs.

2. **Screen Size Frequency:**
   55" and 65" TVs are the most popular models in Australia.
   → These sizes balance screen experience and energy cost.

3. **Brand Market Share:**
   Samsung, Kogan, and LG collectively represent over 70% of models.
   → Targeting these brands could yield the biggest impact for energy-efficiency policies.

4. **Power Consumption vs Screen Size:**
   Larger screens consume more power, with small screens (<80 cm) under 100 W and very large (>200 cm) up to 600 W.
   → Size strongly influences energy use.

5. **Star Rating vs Screen Size:**
   Smaller TVs (<100 cm) often have higher ratings (5–7 stars). Larger TVs show more variation but can still perform well if using newer OLED technology.
   → Energy efficiency decreases with size, but technology matters.

6. **Overall Conclusion:**
   When choosing a TV, balance **brand**, **size**, and **technology**.
   A 55-inch LCD TV is both **common and energy-efficient**, while OLED models offer higher efficiency at larger sizes.

---

## 🤖 AI Declaration

This project was developed with partial assistance from AI tools:

* **ChatGPT (OpenAI GPT-5):** Assisted in refining text explanations, summarising visual insights, and structuring the README document.
* **GitHub Copilot:** Provided syntax support and basic formatting suggestions for HTML and Markdown files.

All **data analysis, interpretation, and chart creation** were completed by the student based on the dataset and class materials.
