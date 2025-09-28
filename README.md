# Mind-Spaks-
Vahan Bazar is a two-wheeler marketplace app where users can browse, compare, and buy bikes or EVs, calculate EMI and fuel costs, book test rides, and sell used bikes. It stands out with resale transparency—tracking theft, service, repaint history—and a mobile-first, dealer-integrated design.
DOCUMENT :
Hackathon Project Document :
Problem Statement ID: HACXPB003
Project Title: Vahan Bazar – Two-Wheeler Marketplace Web App
**Team Name: MIND SPARKS**
Team Members:
•	K SRI VYSHNAVI DEVI
•	K JAYASRI 
•	G YOGITHA 
•	M SAI HARIKA
•	J SUHITHA 
**Problem Statement Summary :**
Build a two-wheeler marketplace web app where users can:
•	Browse bikes, scooters, and EVs
•	Search and filter by brand, price, or fuel type
•	View detailed specs with images
•	Compare models side by side
•	Use EMI and fuel cost calculators
•	Check upcoming launches
•	Explore showrooms
•	Book test rides or sell used bikes
**About the Company – Vahan Bazar :**
Industry: Online Vehicle Selling Platform for Dealerships
Mission: Buy and Sell Bikes in Seconds
Website: https://vahanbazar.app/
Vahan Bazar helps multi-shop dealerships manage inventory, track sales, and grow their business with smart digital tools.
Project Goals : 
•	Create a user-friendly platform for bike discovery and comparison
•	Help users make informed decisions with calculators and specs
•	Enable test ride bookings and used bike listings
•	Support dealers with showroom visibility and inventory tools
**TECH STACKS :**
Frontend-react(with Tailwind CSS for styling)
Backend-Node.js with Express
Datebase-MongoDB(for flexibiliy and scalability)
**Key Features :**
1. Bike Browsing & Filtering
•	Filter by brand, price range, fuel type (Petrol, Electric)
•	Search bar with auto-suggestions
2. Detailed Product Pages
•	Images, specs, price, mileage, reviews
•	“Add to Compare” button
3. Model Comparison
•	Side-by-side view of selected bikes
•	Highlights differences in specs and pricing
4. EMI & Fuel Cost Calculatorsss
•	EMI: Based on price, interest rate, duration
•	Fuel Cost: Based on mileage, fuel price, usage
5. Upcoming Launches & Showrooms
•	List of upcoming models with expected dates
•	Showroom locator with map integration
6. Test Ride Booking & Used Bike Selling
•	Form to book test rides with preferred date/time
•	Upload form for selling used bikes with image and price
**Future Enhancements :**
•	Add user login and profile management
•	Integrate payment gateway for bookings
•	Enable dealer dashboard for inventory uploads
•	Add AI-based recommendation for bikes based on user preferences
**Bonus Differentiators :**
1. Theft History
•	Indicates whether the bike has ever been reported stolen or recovered.
•	Helps buyers avoid risky purchases and ensures legal safety.
Field Name: isReportedStolen
Type: Boolean (Yes/No)
Description: Shows if the bike has any theft cases registered.
2. Service History
•	Tracks how many times the bike has been serviced.
•	Gives buyers insight into maintenance and overall condition.
Field Name: serviceCount
Type: Integer
Description: Total number of official service visits recorded.
3. Repaint History
•	Records how many times the bike has been repainted.
•	Helps assess originality, wear-and-tear, and possible accident history.
Field Name: repaintCount
Type: Integer
Description: Number of times the bike’s body has been repainted.
4. Last Service Date
•	Shows when the bike was last serviced.
•	Useful for estimating upcoming maintenance needs.
Field Name: lastServiceDate
Type: Date
Description: Date of the most recent service entry.
5. Ownership History
•	Displays how many previous owners the bike has had.
•	Adds clarity for buyers seeking low-owner vehicles.
Field Name: previousOwners
Type: Integer
Description: Total number of previous registered owners.
