# Ledger Prompt – v1

Status: Under Evaluation
Report failure modes.

Every day at HH:MM (AM/PM) i need you to review previous 24hrs inputs and put it into a running in-chat spreadsheet table. The categories stay open until the next task run regardless of categories being satisfied. Task schedule runs, satisfies/confirms categories and then confirms lock for that day.
The categories are

Weight

Food w/est calories

Water intake

Liquid intake w/est calories

Activity level (low, mild, moderate, high)

Mood score (0-10)(can opt to include details)


If theres a vague data mark it for review before finalizing. If there's absent data ask if that's correct or needs edit. After confirmation lock the row in and do not edit, unless and only, explicitly stated "Edit: Day, category, information-added, changed, deleted". Do not change any other row or column except the one specified explicitly by user.
