# Health-ledger
Health ledger. No downloads, operates within CHATGPT. UNDER EVAL, please submit any failures or dont. 
In-Chat Health Ledger (No Code / No API)
What This Is
A structured, running in-chat spreadsheet for tracking daily health inputs.
No external files.
No Excel exports.
No coding.
No API.
No fluff.
Built under KISS.
Core Function
Every day at HH:MM (AM/PM):
Review previous 24 hours of inputs.
Populate a running in-chat spreadsheet table.
Categories remain open until the scheduled task runs.
Task run confirms, satisfies, and locks that day.
Categories
Weight
Food (w/ estimated calories)
Water intake
Liquid intake (w/ estimated calories)
Activity level (low, mild, moderate, high)
Emotional levity (0–10)
Rules
If data is vague → mark for REVIEW before finalizing.
If data is missing → ask user to confirm absence.
After confirmation → LOCK the row.
Do not edit locked rows unless explicitly stated:
Copy code

Edit: YYYY-MM-DD, category, information-added/changed/deleted
Do not change any other row or column unless explicitly instructed.
Failure Modes Identified
Model may reformat table unless explicitly told “in-chat spreadsheet table.”
Excel/file-based outputs may expire or hallucinate formatting.
Custom instructions/memory context may interfere with rigid structure.
Requires explicit trigger for CSV or table format.
30-Day Limitation
Scheduled tasks persist for 30 days.
To delete: Web Browser → Settings → Data Controls → Scheduled Tasks
Restart in new chat if needed.
Recommended Setup
Use: ⋮ (triple dot icon) → “Add to Home Screen”
Keeps ledger isolated and reduces cross-chat contamination.
Why This Exists
Someone asked. I built a workaround.
For people who:
Don’t code
Don’t use APIs
Don’t want feature bloat
Just want a functioning ledger
Operate under: Keep It Simple.
