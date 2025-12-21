# Travel Price Tracker  


## Application Definition Statement  
Travel Price Tracker is a web app that helps people save money on trips by watching flight and hotel prices for them. Instead of checking the same trip every day, the user saves a trip once, and the app re checks the prices on a schedule. The app stores price history, and if a price drops, it sends an alert so the user can book at a better time.

## Target Market  
My target market is people who plan trips ahead of time and care about price changes, like students, young adults, and families traveling on a budget. They don’t want to waste time searching the same routes and dates over and over.

**Primary research (what I did):**  
I talked with a few friends and family who travel. Most of them said they either keep checking prices manually, take screenshots, or they give up and just buy because it gets annoying. They liked the idea of “save the trip once and let the app watch it.”

**Secondary research (what I noticed exists):**  
There are apps and websites that help people find deals, but a lot of them still feel like you have to keep checking or it’s not clear why a price changed. My app focuses on tracking, saving history, and sending alerts in a simple way.

## User Profile / Persona  
**Name:** Jasmine R.  
**Age:** 21  
**Background:** College student with a part time job  
**Goal:** Wants to plan a trip without overpaying  
**Frustrations:** Prices keep changing, and she doesn’t know when to buy  
**What she wants:** A simple dashboard where she can save trips, see price history, and get alerts when prices drop 

## Use Cases  

### Use Case 1: Track a flight for a trip  
- User creates an account and logs in  
- User creates a trip (from, to, dates)  
- App shows flight options and prices  
- User selects a flight (or a set of flight details) to track  
- App checks the price automatically on a schedule  
- If the price drops, the app sends an alert  

### Use Case 2: Track a hotel for the same trip  
- User opens the trip they already saved  
- User searches hotels for the trip location and dates  
- App shows hotel options and nightly rates  
- User selects a hotel to track  
- App saves price updates over time  
- If the price drops, the app sends an alert 

## Problem Statement  
People who want to book trips at a good price usually have to check flights and hotels again and again on different websites. This wastes time and makes it easy to miss a deal when prices drop for a short time. From the people I talked to, most of them either get tired of checking or they buy at a random time and hope it was good. 

## Pain Points  
- Checking prices every day is annoying and time consuming  
- It’s hard to tell if a price is actually going down or just changing randomly  
- Most people don’t keep a clean price history, so they can’t compare  
- Deals can show up and disappear fast, so users miss the best time to buy 

## Solution Statement  
Travel Price Tracker solves this by letting users save a trip one time, then the app watches prices for flights and hotels in the background. The app stores price history so it can compare old vs new prices. When the app sees a drop that matches the user’s alert settings, it notifies them so they can book sooner instead of guessing. 

## Competition  
**Direct competition:** Travel tools that show deals or price tracking (like flight search sites and deal apps).  
**Indirect competition:** People using spreadsheets, screenshots, or reminders to track prices themselves.

**How my app is different:**  
My app is built around a trip dashboard that combines flight + hotel tracking together, keeps price history in one place, and focuses on simple alerts so users don’t have to keep checking manually.

## Features & Functionality  
1. **Accounts (Sign up / Login)**  
   Users can create accounts so their trips and alerts are saved.

2. **Trip Builder**  
   Users can create trips with locations and dates so the app knows what to track.

3. **Flight Search and Tracking**  
   Users can search flights and select what they want to track for price changes.

4. **Hotel Search and Tracking**  
   Users can search hotels and select what they want to track for price changes.

5. **Price History**  
   The app saves prices over time so users can see a trend instead of only today’s price.

6. **Price Drop Alerts**  
   Users get notified when prices drop, and can set simple rules like “alert on any drop” or “alert if it drops by $X.”

7. **Dashboard**  
   A main screen to view saved trips, latest prices, and the last time each trip was checked. 

## Integrations  
- **Flight Pricing API:** Used to search flights and get live pricing results  
- **Hotel Pricing API:** Used to search hotels and get nightly rates  
- **Notification Service (Email):** Used to send price drop alerts to the user  


