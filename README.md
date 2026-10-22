# Sport Diet Advisor — AI Chatbot Styled v3

A polished Streamlit UI for the Sport Diet Advisor project.

## Features
- Modern sports-nutrition dashboard
- ChatGPT-style AI nutrition coach
- Persistent SQLite users, profiles and chat history
- Personalized athlete context
- English, Hindi and Hinglish responses
- BMI, BMR, TDEE and protein estimates
- AI food-image scanner
- Quick-action nutrition prompts
- Responsive dark sports theme
- OpenRouter API integration

## Setup

```bash
pip install -r requirements.txt
```

Create `.streamlit/secrets.toml`:

```toml
OPENROUTER_API_KEY = "your_openrouter_api_key"
```

Run:

```bash
streamlit run app.py
```

## Note
Nutrition estimates are general guidance and are not a substitute for professional medical or dietetic advice.


## Ultimate Visual Login
The login screen now includes a cinematic sports-nutrition hero image, glass-style authentication cards, responsive layout, feature pills, and premium green/black branding. The hero image is bundled locally in `assets/sport_nutrition_hero.png`.
