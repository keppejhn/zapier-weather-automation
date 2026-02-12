# Automated Weather Forecast – Zapier Project

This project is a simple daily weather automation built to help me learn how APIs return structured data and how low‑code tools like Zapier handle formatting, scheduling, and logic steps. It sends a local weather email every morning at 7 AM.

## 🎯 Purpose
I created this automation as a hands‑on way to understand:
- How Zapier connects apps through triggers and actions  
- How APIs return structured JSON data  
- How to format and clean data for use in low‑code tools  
- How to design small, reliable automations that run on a schedule  

This project reflects my early steps into automation, data structure, and API concepts.

## 🛠️ Tools & Technologies
- **Zapier** – workflow automation, scheduling, and logic  
- **OpenAI API** – generating a readable weather summary  
- **Weather data source** – structured data returned via API  
- **Email app** – sending the daily forecast  
- **Copilot** – guidance, troubleshooting, and refining prompt structure  

## 📚 What I Learned
Working on this project helped me practice:
- Reading and interpreting structured API responses  
- Formatting JSON into clean, readable email output  
- Using Zapier’s built‑in tools (Formatter, Schedule, Paths)  
- Designing prompts for consistent, predictable summaries  
- Debugging automation steps and validating data inputs  

## 🚀 How It Works
1. **Schedule Trigger:** Zap runs every morning at 7 AM.  
2. **Weather Data:** Zapier retrieves structured weather data.  
3. **AI Summary:** The OpenAI API turns the raw data into a short, readable forecast.  
4. **Email Delivery:** The formatted forecast is sent to my inbox.  

## 📂 Repository Contents
- `README.md` – project overview  
- (Optional) `workflow-diagram.png` – visual outline of the Zap  
- (Optional) `prompt.txt` – the prompt used for the AI summary  
- (Optional) `sample-output.txt` – example of the daily email  

## 🌱 Next Steps
I plan to expand this project by:
- Adding error‑handling steps  
- Logging daily weather summaries into a Notion database  
- Experimenting with additional API fields (humidity, wind, alerts)  

## 📄 License
This project is for personal learning and experimentation. Feel free to reference the structure for your own projects.
