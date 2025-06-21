# HappyCook Game Analytics Dashboard

## Objective  
This project analyzes user behavior and monetization patterns in the mobile game *HappyCook* using Power BI. The goal is to extract actionable insights from player activity, ad views, and in-app purchases to support product and marketing decisions.

## Dataset Overview  
- **User activity**: session counts, play time, level progression  
- **Monetization**: ad views, in-app purchase transactions, revenue type  
- **Geography**: revenue by country  

## Tools Used  
- Power BI (data modeling, DAX, and visualization)  
- Excel (preprocessing and value calculations)

## Dashboard Features  
### 1. **Business Performance**  
- Total revenue: $2.51K across March and April  
- Viewer-only users contribute 33.88% of revenue  
- Top 3 countries: South Korea, United States, Australia  
- Dynamic filters by month

### 2. **Purchase Analysis**  
- In-app purchase revenue: $1.28K  
- Average revenue per buyer: $10.49  
- Monetization funnel: 27.83% viewer rate → 0.24% buyer rate → 0.10% repeat buyer rate  
- Most revenue comes from “Offers” and “Bundles”

### 3. **Player Behavior**  
- 99.15% of users are viewer-only (did not purchase)  
- Day-1 retention: 34.55%  
- Drop-off after level 30 is significant  
- Average revenue per player increases with level  
- Median play time rises in later stages

## Key Insights  
- The conversion rate from viewer to buyer is extremely low (0.24%), suggesting opportunity for better in-game offer timing or onboarding flow.  
- South Korea alone accounts for over 35% of total revenue, indicating a potential regional focus.  
- Average order value and revenue per user are highest around advanced levels (>100), suggesting deeper players are more monetizable.  
- Retention after Day 1 drops rapidly, which could be addressed with early game engagement improvements.

## 🖼 Dashboard Preview  
<img src="images/business_performance.png" width="600"/>  
<img src="images/purchase_in_app.png" width="600"/>  
<img src="images/player_behavior.png" width="600"/>

## 📁 File Structure
