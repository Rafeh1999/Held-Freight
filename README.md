📦 Weekly Held Freight Report – Departure Time Evaluation
This Excel tool is designed for logistics operations involving overnight trailer shifts. It calculates whether each trailer departed Early, On Time, or Late based on its scheduled time, with intelligent handling of departures that cross midnight into the next day.

🕐 Key Features
✅ Handles overnight shifts (e.g., trailers scheduled at 20:00 and departing at 01:30 next day)

✅ Detects:

Late Departure – if more than 2 hours early, or more than 5 minutes late

Early Departure – if within 2 hours before the scheduled time

On Time – exact match or within 5 minutes after scheduled

✅ Accepts Excel time values (no need for full date stamps)

✅ Skips blank entries automatically

🔍 Logic Summary
Condition	Label
More than 2 hours early	Late Departure
Up to 2 hours early	Early Departure
Exact match or ≤ 5 minutes late	On Time
More than 5 minutes late	Late Departure
