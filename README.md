# CarAI – Intelligent Vehicle Insights & Recommendations

CarAI is a full-stack application that helps users get detailed information about their vehicles, personalized upgrade recommendations, maintenance schedules, and local market data. The project follows the **MVC (Model–View–Controller) design pattern** to keep the codebase modular, scalable, and easy to maintain.

---

## ✨ Features

1. **Vehicle Specs Lookup**  
   - Input: `year`, `make`, `model`  
   - Output: engine, drivetrain, dimensions, MPG, trims, performance stats, and key options.

2. **Upgrade Recommendations**  
   - Provides suggestions to make the car **faster**, **more reliable**, or **more efficient**.  
   - Includes tiered plans (e.g., Stage 1–3), estimated costs, expected gains, and reliability impact.

3. **Maintenance Planner**  
   - User adds vehicle + current mileage.  
   - App generates **recommended service intervals** (oil, fluids, brakes, tires, timing belt, etc.).  
   - Provides due-soon alerts based on mileage.

4. **Vehicle Sourcing & Pricing**  
   - Search by `year/make/model` within a radius.  
   - Returns local listings with **pricing analytics** (average, low/high, days-on-market estimate).  

5. **Profiles & Garage**  
   - Users can add multiple vehicles to their profile.  
   - Save upgrade preferences, maintenance history, and recent searches.

---

## 🧩 MVC Structure

- **Models**: Define data entities such as `Vehicle`, `SpecSheet`, `RecommendationPlan`, `MaintenanceSchedule`, and `Listing`.  
- **Views**: Frontend/UI layer to display vehicle data, upgrades, schedules, and listings to the user.  
- **Controllers**: Handle business logic, route requests, and connect models with views (e.g., fetching car specs, calculating service dates, sourcing listings).

---

### Prerequisites
- Node.js (v18+)
- Python 3.11+
- PostgreSQL or MySQL
- Git
