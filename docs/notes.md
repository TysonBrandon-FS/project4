# Project & Portfolio

- **Research Notes – Milestone 3**
- **Brandon Tyson**
- **Assignment Due Date: 12/20/25** 

---

## Topic – Travel Price Tracker (Flight + Hotel Price Alerts)

This document contains general notes related to building my Travel Price Tracker app. The main goal is to let a user save a trip, then the app checks flight and hotel prices over time and alerts the user when prices drop.

---

## Sub-Topic 1 – Flight APIs (Options + Feasibility)

**Brief overview of research:**  
A flight API is what I’ll use to search flights and get live prices. For my project, I need something I can realistically access as a student and that has good docs.

**Key findings:**
- **Amadeus Flight Offers Search** looks very doable because it’s a self-service API, has clear docs, and supports live flight search and pricing. 
- **Skyscanner Travel APIs** exist, but they are more “partner” focused. You usually need to apply and get approved to use them, so access might not be instant for a school project. 
- **Duffel API** can search flights using “offers,” but it feels more business / booking focused. It might be more than I need for an alert app, depending on access and account requirements. 

**My pick for flights (most realistic):**  
**Amadeus** is the best first choice because it’s student friendly and well documented. 

---

## Sub-Topic 2 – Hotel APIs (Options + Feasibility)

**Brief overview of research:**  
A hotel API is what I’ll use to search hotels and pull nightly rates. For my project, I mainly need “search and pricing,” not full hotel management tools.

**Key findings:**
- **Amadeus Hotel Search** is a strong option because it supports hotel search and rates, and it’s in the same platform as the flight API (one account, one general style of docs). 
- **Hotelbeds** looks doable because they advertise getting a free API key and testing in an evaluation environment. That makes it feel more realistic for a student project. 
- **Booking.com APIs** exist, but a lot of their API info is aimed at “connectivity partners” (basically companies managing property data). That doesn’t match my project goal, so it might not be the easiest fit. 

**My pick for hotels (most realistic):**  
Start with **Amadeus Hotel Search**, and keep **Hotelbeds** as a backup if I run into access limits or missing data. 

---

## Sub-Topic 3 – Best Plan for My App (What I’ll Actually Use)

**Brief overview of research:**  
For this project the biggest risk is picking an API that requires a long approval process or a business contract. So I want an option that works fast, has clear docs, and lets me build the core features: search, save, track, alert.

**Key findings:**
- Using **one main provider** for both flights and hotels is simpler because I don’t have to learn two completely different systems. Amadeus supports both categories. 
- Some “big name” travel APIs are **partner-only**, meaning they can reject applications or take time to approve, which is risky for a deadline. 
- Google Flights does **not** have a normal public API anymore, so I should not plan my project around it. 

**My recommended build plan:**
1. **Use Amadeus for flights + hotels first** (fastest path to a working MVP).   
2. Save trip + selections in my database (PostgrSQL).  
3. Add scheduled price checks (ex: every few hours).  
4. Add “price drop” rules and send email alerts.  
5. If I need a backup hotel source later, try **Hotelbeds**. 

---

## Reference Links

Use this section to highlight my independent research and what helped most for this milestone.

**Resource 1: Amadeus Flight Offers Search (Docs)**  
What I learned: This API supports live flight offers and pricing, and the docs are clear enough to build with as a student.  
https://developers.amadeus.com/self-service/category/flights/api-doc/flight-offers-search

**Resource 2: Amadeus Hotel Search (Docs + Guide)**  
What I learned: Amadeus also supports hotel search and rates, which makes it easier to keep flights and hotels in one project.  
https://developers.amadeus.com/self-service/category/hotels/api-doc/hotel-search

**Resource 3: Skyscanner Travel APIs (Partner Docs / Getting Started)**  
What I learned: Skyscanner has travel APIs, but access is partner based and may require approval, so it’s riskier for a school deadline.  
https://www.partners.skyscanner.net/product/travel-api

**Resource 4: Hotelbeds API Suite (Getting Started / Booking API)**  
What I learned: Hotelbeds promotes a free API key and a testing environment, so it could be a realistic backup hotel option.  
https://developer.hotelbeds.com/documentation/getting-started/  
https://developer.hotelbeds.com/documentation/hotels/booking-api/

**Most helpful for this milestone:**  
Amadeus was the most helpful because it covers both flights and hotels, and the docs are straightforward for building a working MVP fast.

