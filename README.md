# Travel Concierge Agent: A Family's AI Trip Planner

**A conversational AI travel planner for families — built with Google ADK and Gemini.**

Built by a mother of four, during a real family vacation, to solve a real problem: planning a stopover in Budapest with three children.

## What it does
This agent has a natural conversation with the traveller — asking about dates, group composition, children's ages, budget, and preferences — then delegates research to six specialised sub-agents (weather, attractions, food, accommodation, transport, and practical tips) to build a complete, personalised day-by-day plan.

## Architecture
One root agent (`travel_concierge`) coordinates six sub-agents, each using Google Search to retrieve real-time information:
- 🌤️ `weather_agent`
- 📍 `attractions_agent`
- 🍽️ `food_agent`
- 🏨 `accommodation_agent`
- 🚌 `transport_agent`
- 💰 `practical_agent`

## Built with
Google Agent Development Kit (ADK) · Gemini 2.5 Flash Lite · Google Search

## How to run

1. Open this project in a Kaggle Notebook
2. Add your `GOOGLE_API_KEY` as a Kaggle Secret (Add-ons → Secrets)
3. Install Google ADK: `pip install google-adk` (pre-installed in Kaggle)
4. Run the cells in order from top to bottom
5. Start chatting with the agent using `runner.run_debug("your message")`

## Full Writeup
See the complete project writeup with architecture details and development journey on Kaggle.
