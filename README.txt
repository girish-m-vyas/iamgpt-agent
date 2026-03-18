==================================================
  IAMGPT — IAM AI Agent (Powered by Google Gemini)
  100% FREE — No credit card needed
==================================================

WHAT YOU NEED
-------------
- Node.js (nodejs.org → LTS version)
- Free Gemini API key (aistudio.google.com)
- Laptop + Mobile on same Wi-Fi


STEP 1 — Get FREE Gemini API Key
---------------------------------
1. Go to: https://aistudio.google.com/app/apikey
2. Sign in with your Google account
3. Click "Create API Key"
4. Copy the key (starts with AIza...)


STEP 2 — Install Node.js (skip if already installed)
------------------------------------------------------
1. Go to: https://nodejs.org
2. Download LTS version → Install it
3. Verify: Open Command Prompt → type: node --version


STEP 3 — Extract this ZIP
--------------------------
Extract iamgpt-gemini.zip to your Desktop
You will get a folder called: iamgpt-gemini


STEP 4 — Add your API Key
--------------------------
1. Open the iamgpt-gemini folder
2. Open .env file in Notepad
3. Replace "your_gemini_api_key_here" with your key:
   GEMINI_API_KEY=AIzaXXXXXXXXXXXXXXX
4. Save the file


STEP 5 — Install & Start
-------------------------
Open Command Prompt and run:

  cd Desktop\iamgpt-gemini
  npm install
  npm start

You will see your laptop URL and mobile IP printed.


STEP 6 — Open in Browser
-------------------------
Laptop : http://localhost:3000
Mobile : http://192.168.x.x:3000  ← shown in terminal
         (must be on same Wi-Fi)


TO STOP THE SERVER
------------------
Press Ctrl + C in the terminal window

TO START AGAIN LATER
--------------------
cd Desktop\iamgpt-gemini
npm start

==================================================
FREE TIER LIMITS (Gemini 1.5 Flash)
==================================================
- 15 requests per minute
- 1,500 requests per day
- 1 million tokens per minute
- No credit card required
==================================================
