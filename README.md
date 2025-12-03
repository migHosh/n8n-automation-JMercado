Phishing Email Detection

This project is an automated email-security workflow built in n8n, combining local AI, cloud AI, an AI Agent, and a Gemini image generator to create a fully styled phishing-assessment report, complete with a 2010s Swag-Era meme.
I have provided three files that basically show how I refined the workflow from my original idea: OG was my first rough draft, Revised came after that, and the FINAL json file is the one I ended up with.

Features:
  Dashboard - vibe-coded using AI-assisted development, allowing rapid iteration of layout, styling, and user experience.
  
  Webhook Email Intake – Receives sender, subject, headers, and body.

  Local AI (Ollama) – Classifies phishing risk as LOW / MEDIUM / HIGH.

  Cloud AI (Perplexity) – Provides a deeper analysis of the email’s content.

  AI Agent (OpenAI) – Cleans, merges, and formats both AIs into a final structured output.

  Conditional Logic (IF) – Chooses a “Danger Meme” or “Safe Meme” depending on risk.

  Gemini Image Generator – Produces a 2010s Swag Era meme (galaxy, snapback, shutter shades, Impact font, etc).

  HTML Render Node – Wraps everything into a clean, styled “Threat Assessment” card.

  Webhook Response – Returns a full HTML page ready for your dashboard or iframe.

