Morning_buddy

Morning_buddy AI is a multi-functional AI-powered city assistant that provides real-time weather updates, personalized news, and smart day planning for any city.
This tool leverages AI to summarize data and create a personalized, interactive experience for users planning their day or visiting a new city.


Features

1. Weather Assistant
- Fetches current weather information using OpenWeather API.
- Converts raw JSON data into human-friendly summaries.
- Provides practical advice on clothing and accessories based on weather conditions.

2. News Aggregator & Summarizer
- Fetches latest news articles based on user-selected topics like Technology, Sports, Health, etc.
- Uses AI to summarize articles concisely for easy reading.

3. Smart City Planner
- Generates a personalized day itinerary for any city.
- Integrates:
  - Weather forecasts
  - Local events
  - Recommended places to visit
- Plans activities chronologically (Morning → Afternoon → Evening) considering weather and event timing.
- Suggests lunch/dinner options and leisure activities.

4. Interactive Web App
- Built using Streamlit.
- Multiple pages:
  - Home (Daily quote & morning image)
  - Weather info
  - News by interest
  - Smart day planner




1.Install dependencies:
pip install -r requirements.txt

2.Create a.env file with your API keys:

GOOGLE_API_KEY=<your_google_gemini_api_key>
OPENWEATHER_API_KEY=<your_openweather_api_key>
NEWS_API_KEY=<your_news_api_key>
LOCAL_EVENT_API_KEY=<your_serpapi_key>

3.Run the Streamlit app:
streamlit run app.py

4.Navigate through sidebar to:
-Check weather
-Fetch news by interest
-Generate personalized city itinerar

Technologies Used

Python 3.x
Streamlit
Google Gemini AI
OpenWeather API
NewsAPI
SerpAPI

