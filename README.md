# ✈️ AI Travel Itinerary Planner

CS4680 Prompt Engineering Final Project - An AI-powered web app that generates personalized travel itineraries in seconds.

## Problem Statement

Trip planning is time-consuming and overwhelming. Travelers struggle with information overload, generic recommendations, and difficulty balancing interests with budget constraints. This app solves these problems by generating personalized, expert-level itineraries instantly.

## Features

- Personalized day-by-day itineraries based on interests, budget, and travel pace
- Detailed explanations for each recommendation
- Budget breakdowns and insider tips
- Download itineraries for offline use
- Clean, responsive UI

## Prompt Engineering Techniques

### 1. Persona Pattern
Creates an expert travel guide persona with 15+ years of experience. Adapts recommendations based on budget level (street food for budget travelers, fine dining for luxury) and pace preferences.

**Location**: `buildSystemPrompt()` function

### 2. Template/Few-Shot Pattern
Provides structured output format with clear sections (Overview, Day-by-Day, Budget Breakdown, Insider Tips, Packing List). Ensures consistent, well-organized itineraries.

**Location**: `buildUserPrompt()` function

## Tech Stack

- **Frontend**: HTML, JavaScript, Tailwind CSS
- **AI**: DeepSeek via OpenRouter API (100x cheaper than GPT-4)
- **Deployment**: GitHub Pages

## Setup

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/ai-travel-planner.git
   ```

2. Get OpenRouter API key at [openrouter.ai/keys](https://openrouter.ai/keys)

3. Add your API key to `travel-planner.html`:
   ```javascript
   const OPENROUTER_API_KEY = 'sk-or-v1-your-key-here';
   ```

4. Open `travel-planner.html` in your browser

## Usage

1. Enter destination and trip duration
2. Select budget level (Budget/Moderate/Luxury)
3. Choose interests (Food, History, Nature, etc.)
4. Add any special requirements
5. Click "Generate My Itinerary"

## Author

**Natasha Wong** - CS4680 Fall 2025