# UYAN Inventory Shared Web v5

Responsive UYAN inventory system for phone and computer.

Key workflow:
- Food and Drinks/Bar inventories are separate.
- Food and Drinks have independent permanent item numbers.
- New items receive the next permanent number; old numbers are never reused.
- Main stock shows Opening Stock, Confirmed New Stock, Total Stock, Issued Today, Balance and Low Stock.
- New supplies remain Pending until a receiver confirms them; only confirmed quantities enter inventory.
- Short deliveries are visibly flagged.
- Kitchen issues are recorded per individual chef and can be printed per chef/date.
- Bar issues are recorded per individual bar staff and can be printed per person/date.
- One Storekeeper manages both Food and Drinks.
- No cashier role.
- Existing UYAN logo retained.

Demo accounts:
- admin / admin123
- storekeeper / store123

Run:
`npm install && npm start`
