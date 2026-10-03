# Pick Us: Effortless Travel Discovery & Booking

A responsive travel discovery and booking web app that helps people explore destinations, compare experience tiers, pick hotel rooms by view, and plan a full trip with live pricing in INR.

**Live demo:** https://pick-us-effortless-travel-discovery-booking.ai.studio/

## Features

- **8 destinations** across India and international: Goa, Munnar, Kerala Backwaters, Manali, Bali, Maldives, Dubai and Paris
- **24 curated hotels** with star ratings, view labels (sea, mountain, sunset, city), room categories and guest capacity
- **Tier toggle:** switch between Budget, Comfort and Luxury to see prices change across every destination
- **Search and filters:** search by destination name and filter by region (India or International)
- **Destination details:** itinerary highlights, top attractions with entry fees, best season to visit, and hotels
- **Plan My Trip:** a multi-step planner that calculates the total live in INR from destination, dates, travellers, tier, room view and sightseeing passes
- **Coupon support:** apply `PICKUS2000` for ₹2,000 off
- **Booking flow:** instant booking with a reference code (`PU-XXXXXX`)
- **Profile drawer:** view active bookings, membership tier, and printable receipts
- **Responsive design** for desktop and mobile

## Tech Stack

- **Design:** Google Stitch
- **Build:** Google AI Studio (Build mode)
- **Frontend:** React, Tailwind CSS
- **Data:** local JSON dataset (destinations, hotels, rooms, prices)

## How It Was Built

1. Designed the UI screens in Google Stitch (colour palette, layout, components).
2. Sent the design to Google AI Studio and turned it into a working app with prompt-driven iteration.
3. Added filters, live price calculation, coupon logic and the booking flow feature by feature.
4. Fixed layout issues (overlapping text, sticky images), replaced broken image links, and published the app.

## Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/fatimaalruhala/pickus-travel-website.git
cd pickus-travel-website

# 2. Install dependencies
npm install

# 3. Start the development server
npm run dev
```

Then open the local URL shown in the terminal (usually http://localhost:3000 or http://localhost:5173).

> If the project uses any API key, create a `.env.local` file and add your own key there. Never commit this file to GitHub.

## Try It

1. Open **Plan My Trip** and choose a destination.
2. Change dates, travellers and the tier, and watch the total update.
3. Apply the coupon `PICKUS2000`.
4. Confirm the booking and open the profile drawer to view the receipt.

## Future Improvements

- User login and saved trips with Firebase
- Real payment gateway integration (Razorpay or Stripe)
- Live hotel and flight prices from a travel API
- Reviews and ratings from travellers
- Wishlist and destination comparison

## Note

All prices, hotels and bookings are sample data created for demonstration. No real bookings or payments are processed.

## Author

**[Your Name]**
GitHub: [fatimaalruhala](https://github.com/fatimaalruhala)
