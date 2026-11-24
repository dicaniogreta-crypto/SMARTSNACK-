# SMARTSNACK-
An AI-powered web application built with **Softr** that helps high school students choose balanced snacks during school breaks by analyzing food images and providing nutritional insights.

* **Live App (Softr):** [https://smart-snack.mysoftr.app]
* **Demo Video:** [https://drive.google.com/file/d/1cLAVsEDm2Q2E27UiG7LOohpnxSH-UEV_/view?usp=drivesdk]

---

## 🎯 Problem
During short school breaks, students often grab ultra-processed snacks without knowing their nutritional value, sugar content, or potential allergens. Reading complex nutrition labels takes time, and homemade or unpackaged snacks don't have labels at all.

## ⚙️ Mechanism (How It Works)
1. **Image Capture:** The user uploads or takes a photo of their snack through the Softr web interface.
2. **AI Vision & Nutritional Analysis:** The image is processed by an AI vision model that identifies the food item and retrieves estimated macronutrients (proteins, carbs, fats, sugars) and common allergens.
3. **Student-Friendly Feedback:** The app translates raw numbers into clear, supportive advice focused on sustained energy and concentration for classes.

## 📊 Data & Edge Case Testing
* **Data Sources:** Nutritional estimates are based on standard food composition references and visual recognition of common school snacks.
* **Edge Cases Tested:** We tested the prototype with 5 unexpected inputs, including blurry photos, unpackaged bakery items, beverages, non-food objects, and multi-snack plates to ensure the agent asks for confirmation instead of guessing.

## ⚠️ Limitations
* **Allergen Safety:** Visual analysis cannot detect hidden ingredients or cross-contamination (e.g., traces of nuts or gluten).
* **Unpackaged Foods:** Accuracy decreases for homemade recipes or local artisanal snacks without standard packaging.

## 🛡️ Ethics Review
Read our full ethical reflection—covering allergen risks, healthy relationship with food, design safeguards, and honest limitations—in our [Ethics Review](./ethics-review.md).
