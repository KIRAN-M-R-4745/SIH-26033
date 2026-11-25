# Smart India Hackathon Workshop
# Date:
## Reference Number:
## Name:

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
An app where farmers sell directly to buyers, with no middlemen.

Today:   Farmer -> Trader -> Agent -> Wholesaler -> Retailer -> Consumer

Ours:    Farmer -> App -> Local Hub -> Buyer

1. Farmer lists crops in the app (voice, local language).
2. Buyer orders and pays by UPI.
3. A local hub delivers the order.
4. AI suggests prices, predicts demand and plans routes

## Technical Approach

1. Technologies to be used

* Mobile app and website: Flutter and React
* Backend: Python (FastAPI) with PostgreSQL
* AI: Prophet (demand prediction), Google OR-Tools (delivery routes)
* Payments and maps: UPI and OpenStreetMap

2. Methodology and process for implementation

Flow chart:
Farmer lists crop in app
          |
          v
AI suggests fair price
          |
          v
Buyer orders and pays by UPI
          |
          v
Local hub picks up the produce
          |
          v
AI plans the delivery route
          |
          v
Buyer receives the order
          |
          v
Farmer is paid directly

Steps to build it:

1. Build a working prototype: list crops, place orders, pay.
2. Add AI for price tips, demand prediction and delivery routes.
3. Test with a few FPOs and buyers in one district.
4. Improve from feedback, then scale.


## Feasibility and Viability
1. Uses simple, low-cost tools.
2. Challenge: farmers new to apps. Solution: voice support and help from FPOs.
3. Start with one district.
 
## Impact and Benefits

1. Farmers earn more and get paid quickly.
2. Consumers get fresh produce at lower prices.
3. Less food waste.
## Research and References
Remove These Lines
1. https://agmarknet.gov.in
2. https://enam.gov.in
3. https://ondc.org
