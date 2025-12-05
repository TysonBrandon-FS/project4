# Travel Price Tracker (Milestone 1)

## What my app is supposed to do
My app will track flight prices and hotel prices for trips the user wants to take. The app should alert the user when a price drops so they can buy it at the best time. The goal is to help people save money without checking prices every day.

---

## Flight API Options

### 1. Amadeus API
- Has flight search and price info.
- Gives real airline prices.
- Has a free tier for testing.

### 2. Skyscanner API
- Good for comparing flights from many airlines.
- Shows prices from travel sites like Expedia.
- Might require approval to access.

### 3. AviationStack
- Mostly for flight status.
- Not great for price tracking.

**Best choice:** Amadeus, because it supports price search and is easier for students to use.

---

## Hotel API Options

### 1. Amadeus Hotel Search
- Works the same way as their flight API.
- Lets me search hotels and get nightly rates.
- Good because everything stays in one system.

### 2. Booking.com API
- Has hotel prices but is harder to get access.
- Probably not the best choice for this project.

### 3. RapidAPI Travel APIs
- Has lots of small hotel APIs.
- Easy to access but not always reliable.

**Best choice:** Amadeus again, since it keeps things simple and consistent.

---

## How price tracking will work
The user will enter:
- Where they want to go  
- The travel dates  
- Their budget  

My app will:
1. Check API prices on a schedule.  
2. Save the lowest price in MongoDB.  
3. Compare new prices with old ones.  
4. Alert the user if the price drops.

---

## Tech Stack I want to use
- **Frontend:** React  
- **Backend:** Node + Express  
- **Database:** MongoDB  
- **API Requests:** Axios  
- **Hosting:** Netlify or Render  

---

## Challenges I might run into
- Some APIs might not be fully free.
- Flight data can be confusing.
- API rate limits might slow things down.
- I need to figure out how to run price checks on a timer.

---

## Why this project makes sense
- Price-tracking apps already exist, so the idea is realistic.
- React, Node, and MongoDB work well for dashboard apps.
- Amadeus has enough free features to build a working version.

