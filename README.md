# 📊 AI-Powered Product-Level Sales Trend Analysis

Transform raw retail sales data into **actionable business intelligence** using AI.

---

# 🎯 Problem Statement

Retail businesses often struggle with:

### 1️⃣ Manual Data Analysis
- Sales data stored in CSV/Excel files
- Manual trend analysis is time-consuming
- Requires skilled analysts

### 2️⃣ Lack of Trend Visibility
- Difficult to identify growing vs declining products
- No clarity on stable performers
- Seasonal patterns go unnoticed

### 3️⃣ Inventory Management Issues
- Overstocking slow-moving products
- Stock-outs for high-demand products
- Poor reorder planning

### 4️⃣ Branch Performance Gaps
- Hard to compare sales across branches
- No unified demand view
- Weak data-driven decisions

---

# 💡 Proposed Solution

This project uses **Artificial Intelligence (AI)** to:

- Analyze product-wise sales trends
- Identify growing, declining, and stable products
- Compare branch-wise performance
- Generate business-ready insights
- Support inventory & strategic planning

The system converts **raw sales data into actionable intelligence** using Nexus AI models.

---

# 🤖 AI Models & Modalities

## 1️⃣ Sales Trend Analysis

- **Modality:** Text → Text  
- **Model Used:** `gpt-4.1-nano`  
- **Provider:** OpenAI (via Nexus AI)  

### Why This Model?
- Efficient structured data reasoning
- Clear business explanations
- Cost-effective & fast
- Ideal for retail analytics pipelines

---

## 2️⃣ Branch Comparison & Graph Generation

- **Modality:** Text → Code (Matplotlib Visualization)
- **Model Used:** `gpt-4.1-nano`
- **Provider:** OpenAI (via Nexus AI)

### What It Does:
- Generates grouped bar charts
- Identifies better-performing branches
- Detects underperforming locations
- Suggests inventory strategies

---

## 3️⃣ Audio Summary (Accessibility Feature)

- **Modality:** Text → Audio
- **Model Used:** `gpt-4o-mini-tts`
- **Provider:** OpenAI (via Nexus AI)

### Benefits:
- Converts insights into speech
- Supports visually impaired users
- Enables voice-based dashboard summaries

---

# 🔄 Data Flow Architecture

## 🧾 1️⃣ Input Processing
- CSV Upload
- Product & branch selection
- Data validation

## ⚙️ 2️⃣ Processing Pipeline
- Product-level trend analysis
- Branch-wise comparison
- Inventory risk detection
- Strategy recommendation

## 🧠 3️⃣ Decision Engine
- Growth / Decline classification
- Demand stability detection
- Restocking suggestions

## 📤 4️⃣ Output Generation
- Business insights (Text)
- Visual charts (Matplotlib)
- Audio summaries (MP3)

---

# 📂 Dataset Used

**File Name:**  
`food_shop_annual_sales_regionwise (1).csv`

### Contains:
- Product names
- Branch-wise sales
- Time-based patterns

---

# 📈 Task 1 – Product-Level Sales Analysis

The AI evaluates:

- Overall sales performance
- Monthly trends
- Seasonality insights
- Day-of-week demand patterns
- Inventory risks
- Growth opportunities

### Output Format:
- Bullet-based insights
- Clear reasoning
- Actionable business recommendations

---

# 🏬 Task 2 – Branch-Wise Comparison

### AI Generates:
- Grouped bar charts
- Product vs branch comparison
- High-demand vs low-demand detection
- Inventory risk insights
- Restocking recommendations

### Visualization Requirements:
- Matplotlib only
- Side-by-side grouped bars
- Rotated product labels
- Title + legend

---

# 🔊 Accessibility & Audio Insights

The system generates:

- Text summary of performance
- Auto-generated MP3 file
- Voice-enabled sales reporting

Example Output:
> "Sales analysis completed. Branch A has the highest overall sales..."

---

# 🔗 Nexus AI API Integration

## About Nexus AI

Nexus AI acts as a **unified gateway** that:

- Provides OpenAI-compatible interface
- Allows multi-model access
- Enables scalable AI pipelines
- Supports multimodal capabilities

---

# 🛠️ Installation

```bash
pip install openai pandas matplotlib streamlit pypdf
```

---

# ▶️ How to Run

1. Upload CSV file
2. Enter product name
3. Select two branches
4. View:
   - AI insights
   - Generated charts
   - Audio summary file

---

# 🏗️ Tech Stack

- Python
- Pandas
- Matplotlib
- OpenAI API (via Nexus AI)
- GPT Models
- Text-to-Speech (TTS)

---

# 📊 Business Impact

This system enables:

✅ Data-driven inventory planning  
✅ Reduced overstock & stock-outs  
✅ Branch performance benchmarking  
✅ Faster executive decisions  
✅ Accessibility inclusion  


---

# 🚀 Future Enhancements

- Streamlit Dashboard UI
- Real-time analytics
- Seasonal forecasting model
- Anomaly detection
- Cloud deployment

---

# 👨‍💻 Author

RAAJA HARI VIGNESH S
