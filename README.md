# Multilingual Budget & Expenses Tracker

## Overview
The Multilingual Budget & Expenses Tracker is an innovative Python-based application designed to help users manage their expenses effectively in multiple languages. It enables users to set budgets, track expenses, analyze spending patterns, and receive alerts when budgets are exceeded. The application also provides detailed visualizations and summary statistics to offer insights into spending habits.

---

## Features

### 🏦 Multilingual Support
- Translate text and alerts to Urdu, Arabic, Hindi, and English.
- Leverages pre-trained translation models from Helsinki-NLP.

### 💰 Budget Setting
- Define a monthly budget in PKR.
- Alerts for budget violations with audio notifications.

### ➕ Expense Tracking
- Add expenses across predefined categories.
- Automatic saving calculation based on remaining budget.

### 📊 Data Visualization
- Pie chart of expense distribution by category.
- Line chart of monthly expense trends.
- Bar chart comparing expenses across categories.
- Boxplot for expense distributions.

### 📝 Detailed Analysis
- Comprehensive statistics including total, average, and median expenses.
- Breakdown of expenses by category and month.

---

## Installation
To get started, clone the repository and install the required dependencies:

```bash
pip install gtts
pip install playsound
pip install gradio
pip install transformers
pip install torch
```

---

## How to Use
1. **Run the Application:**
   Launch the interface by running the script in your Python environment:
   ```python
   python multilingual_budget_tracker.py
   ```
2. **Interact via Gradio:**
   - Use the web-based interface to set budgets, add expenses, and visualize data.

3. **Interface Overview:**
   - **Budget Setting Tab:** Set your monthly budget in PKR.
   - **Add Expenses Tab:** Add expenses across multiple categories and view alerts.
   - **Visualizations Tab:** Generate charts for a better understanding of your spending.
   - **Summary Statistics Tab:** View detailed insights and summary statistics.

---

## Key Components

### Libraries Used
- **Gradio:** Interactive web-based interface.
- **Transformers:** Pre-trained models for translation.
- **Torch:** Backend for deep learning models.
- **gTTS:** Text-to-speech for audio alerts.
- **Matplotlib & Seaborn:** Data visualization tools.

### Pre-trained Models
- Translation models:
  - `Helsinki-NLP/opus-mt-en-ur` (English to Urdu)
  - `Helsinki-NLP/opus-mt-en-ar` (English to Arabic)
  - `Helsinki-NLP/opus-mt-en-hi` (English to Hindi)

### Expense Categories
- Food, Transport, Bills, Entertainment, Education, etc.

---

## File Structure
- **main.py**: Contains the main application logic.
- **requirements.txt**: List of required Python libraries.
- **assets/**: Contains generated visualizations and alerts.

---

## Future Enhancements
- Support for additional languages.
- Integration with mobile apps.
- AI-based budget optimization suggestions.

## Team Members
Ehtijad Ali Shah
Sartaj Ali
Badar Muneem
Almeen 
Saqlain Nissa
