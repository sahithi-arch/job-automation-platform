"""
Installation & Setup Guide for Job Automation Platform
"""

# STEP 1: Install Required Packages
# Run in terminal:
# pip install fastapi uvicorn python-dotenv openai sqlalchemy psycopg2-binary pydantic apscheduler twilio python-dateutil pytz

# STEP 2: Update .env file with your info
# OPENAI_API_KEY=your_openai_key
# USER_EMAIL=your_email@gmail.com
# USER_PHONE_NUMBER=+1XXXXXXXXXX (your phone number for call notifications)
# TWILIO_ACCOUNT_SID=your_twilio_account_sid
# TWILIO_AUTH_TOKEN=your_twilio_auth_token
# TWILIO_PHONE_NUMBER=+1XXXXXXXXXX (Twilio number)
# GMAIL_EMAIL=your_gmail@gmail.com
# GMAIL_PASSWORD=your_gmail_app_password

# STEP 3: Start PostgreSQL
# brew services start postgresql@15

# STEP 4: Create Database
# createdb job_applications

# STEP 5: Run Backend
# cd backend
# python -m uvicorn app:app --host 0.0.0.0 --port 8000 --reload

# STEP 6: Run Frontend (new terminal window)
# cd frontend
# npm run dev

# STEP 7: Access Dashboard
# http://localhost:3000

print("""
╔════════════════════════════════════════════════════════════════════════════╗
║                                                                            ║
║           🤖 JOB AUTOMATION PLATFORM - SETUP GUIDE                        ║
║                                                                            ║
║  ✅ AUTOMATIC DAILY OPERATIONS                                            ║
║                                                                            ║
║  📅 SCHEDULE:                                                              ║
║     Morning:  6 AM - 5 PM CST (every 2 hours)                             ║
║     Evening:  10 PM - 1 AM CST (every 2 hours)                            ║
║                                                                            ║
║  ⚙️  WHAT HAPPENS AUTOMATICALLY:                                           ║
║     1. Scrapes 100+ jobs for AI/Data Engineer roles                       ║
║     2. Filters with AI (only relevant positions)                          ║
║     3. Auto-applies to matching jobs                                      ║
║     4. Makes AI phone calls to companies                                  ║
║     5. Schedules interviews                                               ║
║     6. Sends you daily email reports with counts                          ║
║                                                                            ║
║  📊 DAILY EMAIL INCLUDES:                                                  ║
║     ✓ Applications sent (count)                                           ║
║     ✓ Phone calls made (count)                                            ║
║     ✓ Interviews scheduled (count)                                        ║
║     ✓ Interview dates & times                                             ║
║     ✓ Company names & positions                                           ║
║                                                                            ║
║  🔍 JOB SEARCH KEYWORDS:                                                   ║
║     • AI Engineer                                                         ║
║     • Machine Learning Engineer                                           ║
║     • Data Engineer                                                       ║
║     • Data Scientist                                                      ║
║     • AI/ML Engineer                                                      ║
║     • LLM Engineer                                                        ║
║     • NLP Engineer                                                        ║
║     • Computer Vision Engineer                                            ║
║                                                                            ║
║  📍 LOCATIONS:                                                             ║
║     • Remote                                                              ║
║     • US-based (all major tech hubs)                                      ║
║                                                                            ║
║  💼 JOB TYPES:                                                             ║
║     • Full-time                                                           ║
║     • Contract                                                            ║
║                                                                            ║
║  🌐 JOB SITES MONITORED:                                                   ║
║     • LinkedIn                                                            ║
║     • Indeed                                                              ║
║     • Glassdoor                                                           ║
║     • Built.in                                                            ║
║     • TechCrunch Jobs                                                     ║
║                                                                            ║
║  📞 PHONE CALL FEATURES:                                                   ║
║     • AI-generated professional scripts                                   ║
║     • Automated screening questions                                       ║
║     • Interview scheduling with available times                          ║
║     • Call transcripts saved                                              ║
║                                                                            ║
║  🚀 NO MANUAL WORK NEEDED!                                                 ║
║     Just set it up once and let it run 24/7                               ║
║                                                                            ║
╚════════════════════════════════════════════════════════════════════════════╝
""")
