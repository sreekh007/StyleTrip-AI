# StyleTrip AI – Travel Outfit Recommendation System

## About the Project

StyleTrip AI is a travel outfit recommendation application developed using Python, Streamlit, and Google's Gemini AI.

Planning outfits for a trip can be difficult, especially when travelling to different places with different weather conditions and activities. This project aims to make that process easier by suggesting suitable outfits based on the user's travel plans and personal preferences.

Users can enter their destination, number of travel days, expected weather, activities, preferred fashion style, and budget. Based on these details, the application generates outfit suggestions for each day of the trip.

## Features

- Daily outfit recommendations based on trip duration.
- Outfit suggestions according to manually entered weather conditions.
- Different fashion styles such as Korean, Western, Casual, Traditional, and Streetwear.
- Clothing, footwear, and accessory recommendations.
- Colour combinations and styling suggestions.
- Packing checklist for the trip.
- Budget-based outfit suggestions.
- Quick summary of daily outfits.
- Option to download the generated outfit plan.

## Technologies Used

- Python
- Streamlit
- Google Gemini API
- Google Gen AI SDK

## How to Run the Project

**1. Clone the repository**

```bash
git clone https://github.com/sreekh007/StyleTrip-AI.git
```

**2. Open the project folder**

```bash
cd StyleTrip-AI
```

**3. Install the required libraries**

```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
streamlit run app.py
```

**5. Enter your Gemini API key**

Provide a valid Gemini API key in the application sidebar to generate outfit recommendations.

API key: https://aistudio.google.com/apikey

## How the Application Works

1. The user enters their travel destination and trip duration.
2. Expected weather conditions and travel activities are provided.
3. The user selects their preferred fashion style, clothing preferences, and budget.
4. Gemini AI processes the inputs and generates suitable outfit recommendations.
5. The application displays daily outfits, styling tips, and a packing checklist.

## Note

Weather conditions are entered manually by the user. The outfit recommendations are generated using the Gemini API.

