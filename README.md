# 🩺 Personalized Food Analyzer AI (Powered by Google Gemini Gems)

> A simple, personalized food-analysis tool that uses your health data to rate foods and suggest better choices.

[![Gemini](https://img.shields.io/badge/Powered%20by-Google%20Gemini-8E75B2?style=for-the-badge&logo=google-gemini)](https://gemini.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

## 🧐 What is this?

A lightweight AI tool that analyzes food images and gives you a rating based on **your personal health profile**.  
It considers your goals, biomarkers (like LDL, iron, liver markers), allergies, and activity level.  
The aim is simple: help you understand how a specific food affects *your* body and offer suitable alternatives when needed.

### Key Features
- Uses your biomarker data for personalized ratings  
- Flags allergens, sensitivities, or conflicts with your profile  
- Highlights hidden issues (excess sugar, refined carbs, poor-quality fats)  
- Suggests practical alternatives when a food rates low  
- Adjusts portion guidance based on height, weight, and activity  
- Works on any device using the Gemini app

---

## 📸 Visual Proof: The Engine in Action

| The "2-Minute" Trap | The "Comfort" Drink | The Street Food King |
| :---: | :---: | :---: |
| <img src="assets/01_eg_maggi.png" width="250" alt="Maggi Analysis"> | <img src="assets/02_eg_chai.png" width="250" alt="Chai Analysis"> | <img src="assets/03_eg_vada_pav.png" width="250" alt="Vada Pav Analysis"> |
| **Rating: ⭐ (1/5)**<br>Refined carbs and unhealthy fats aggressively target already high LDL and stressed liver. | **Rating: ⭐ (1/5)**<br>Sugar spikes insulin; tannins block iron absorption needed for low ferritin levels. | **Rating: ⭐ (1/5)**<br>Deep-fried preparation is catastrophic for cholesterol goals and liver inflammation. |

---

## 🚀 Setup Guide: Create Your Personal Gem

You need a Google account with Gemini Advanced to create custom Gems.

### Step 1: Generate Your Profile  
This creates a clean configuration block from your health data.

1. Collect your information: blood reports, height/weight, goals, allergies, supplements.
2. Open a chat in Gemini.
3. Paste the **Profile Generator Prompt**:  
   👉 `prompts/01_profile_generator.md`
4. Provide your health details when asked.
5. Copy the final code block output. You’ll need it in Step 2.

### Step 2: Set Up the Food Analyzer Gem

1. Open **Gem Manager** → **New Gem**.
2. Name your Gem (e.g., “Food Analyzer”).
3. Paste the **Food Analyzer Prompt**:  
   👉 `prompts/02_food_analyzer.md`
4. Scroll to the section marked:  
   `# [INSTRUCTION FOR USER: PASTE THE OUTPUT FROM 'STEP 1: PROFILE GENERATOR' BELOW]`
5. Delete that instruction line and paste your profile block there.
6. Save the Gem.

---

## 💡 Usage Tips

- Providing short text along with the image improves accuracy  
  (e.g., “homemade, low oil”, “restaurant, ate half portion”).  
- Use the most capable Gemini model available in your account.  
- You can pin the Gem to your home screen for quick access.

<p align="center">
  <img src="assets/how_to_pin_app.png" alt="How to pin Gemini Gem to home screen" width="700">
</p>

---

## ⚠️ Disclaimer

This tool provides general nutritional insights based on the data you supply.  
It is **not** a medical device or a replacement for professional medical advice.  
Always consult a qualified healthcare provider for medical guidance.