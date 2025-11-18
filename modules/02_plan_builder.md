Change Log (2025-11-18): Refined Module 02 based on AI critique: set distance rules, added a theme list, and expanded the activity details.

### **Module 2 — Plan Builder (Options → Days)**

Create a short list of candidate activities (e.g., attractions, restaurants, parks).  
Each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:  
    pick Morning activity (near lodging)  
    pick Midday activity (close by)  
    pick Afternoon activity (different theme)  
    pick Evening restaurant or optional event

Each activity should list:
  Name + type (museum, park, restaurant, etc.)
  Duration (how long it takes)
  Cost range (free, , $, $$$)
  Distance from lodging
  Opening hours + weather notes (indoor/outdoor)

Rules for Picking:
  Morning: very close to lodging (≤15 min walk/ride)
  Midday: nearby from morning spot (≤25 min)
  Afternoon: different type/theme than earlier activities
  Evening: restaurant or event, check reservations and dietary needs
