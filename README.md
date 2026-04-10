**AI-Powered Last-Mile Delivery Optimizer**

**This project is now officially open for open-source contributions**

✨Walmart Sparkathon Focused

✅ **Problem Statement** 
- Retailers and e-commerce giants like Walmart face significant challenges in last-mile delivery, especially during high-demand events (festivals, emergencies, traffic congestion).
- Delays, inefficient routing, high carbon emissions, and poor real-time coordination with delivery agents are major bottlenecks.
----
✅ **Solution** 
  Built an intelligent, modular, and scalable dashboard that:
- Optimizes delivery routes in real-time
-  Supports Emergency Mode, 🎉 Festival Mode, and future AI toggles
- Works even in offline mode with local caching
- Tracks agent GPS live
- Calculates fuel and CO₂ savings
- Includes a smart AI chatbot assistant for delivery managers
----
**This is not a customer-facing app.**

✨ **It’s a plug-and-play AI-powered dashboard for Walmart’s internal last-mile delivery operations, designed to help managers reduce delays, costs, and carbon emissions while improving visibility.**
----
⭐ **What Sets Us Apart** ⭐
- A truly plug-and-play system — easy to integrate without overhauling Walmart’s existing tools
- Works offline, supports live GPS, and is extremely modular
- Not just analytics — it acts, by intelligently optimizing delivery plans and helping reduce operational chaos
- Supports real-time AI-based delay predictions, risk scoring, and sustainability tracking
- Built with scalability in mind — works across zones, cities, and third-party partners
- Even saving ₹10–15 fuel cost per delivery, when scaled to 1 lakh+ daily deliveries, can save Walmart over ₹1 crore every month — purely from smarter routing, consolidation, and delay mitigation .
- Our solution makes that possible — in a plug-and-play, AI-powered, and GPS-aware dashboard.
----
  **Key Features** 
- **AI-Powered Optimization**
  Predicts delivery delays using zone, distance, and seasonal factors
  Computes risk scores for each order
- **Smart Consolidation**
  Suggests grouped deliveries for similar localities and short distances
- **Displays consolidation summary + AI-generated suggestions**
- **Emergency / Festival Mode**
  On one click, apply optimization to minimize high-risk zones (e.g., Koramangala)
- **Easy to extend with new modes** (Rain Mode, Traffic Mode, Partner Priority Mode)
- **Real-Time GPS Tracking**
  Uses live agent GPS to improve visibility
- **ETA Countdown & Risk Monitoring**
  Each order has live ETA countdown, delay severity badge, and zone-based risk flagging
- **Sustainability Metrics**
  Calculates fuel and CO₂ savings from optimized routes
- 🧑‍💻 **Smart Chatbot Assistant**
  Provides help and suggestions for dashboard usage
  Answers common delivery/logistics questions (React-component based)
-  **Offline Mode**
  Works seamlessly when internet is unavailable using localStorage caching
- **Delivery Agent App** (Companion)
  Mobile-friendly interface for agents to view assigned orders, optimized routes, and update delivery status
  Helps reduce confusion, delays, and syncs live with the main dashboard  
----
 **Why This Solution is Plug-and-Play** 
 ⚡Companies can adopt it without rewriting existing tools
    No hard dependency on internal APIs — can connect via Supabase, REST, or partner APIs
    Uses simple JSON/mockOrder format that real systems can map to easily
 ⚡Extremely Modular Code
   Each function and feature is decoupled
   AI modes are plug functions like applyEmergencyMode() or applyRainyMode()
 ⚡No Vendor Lock-in
   Backend is Supabase (PostgreSQL) → Can switch to any backend
   Frontend is React + Tailwind → Works with any modern stack
   
   ----
 **Scalability & Upgradeability** 
⚡ Can Handle 1000s of Deliveries per Hour
     Efficient rendering (React + Tailwind UI)
     Grouping and filtering logic already optimized
     Uses minimal external dependencies (low overhead)
⚡**Add New Delivery Partners Easily**
   Integrate via API or CSV → maps to existing format
   UI adjusts dynamically based on zone, partner, distance
⚡**Add New Cities / Zones**
   Our system uses zone fields — adding a new city is plug-and-play
   No core logic changes required
⚡**Add More AI Modes Anytime**
   Already supports toggles for Emergency / Festival
   Can easily add: Rain Mode, Peak Hour Mode, Partner Priority Mode etc.
   ✅ Just plug new logic file → toggle UI → done. 

----

✨ **We’re also looking forward to making this solution more scalable for real-world operations
by integrating live delivery systems, expanding to more cities, and adapting to dynamic business needs at scale.**

----
🛠 **Tech Stack** 
**Frontend:** React.js + Tailwind CSS
**Backend:** Supabase (PostgreSQL + API)
**Hosting:** Vercel (or Netlify/AWS/GCP)
**Map**: Static coordinates for demo, GPS via browser
**AI:** Rule-based predictors + delay scorers (can upgrade to ML models)

----
 Final Pitch Statement
**“Our solution is AI-powered, offline-resilient, GPS-aware, and scalable across cities, partners, and use cases — giving Walmart a plug-and-play delivery optimizer ready for real-world operations.”**

----
 **Built For:** 
 E-Commerce
 Hyperlocal Delivery
 Logistics Tech
 Walmart Sparkathon 

----
**👩‍💻 Author**
**Shailaja Poojary**
Creator & Maintainer of the AI Last-Mile Delivery Optimizer

----
**HOW TO RUN**
'''bash
Clone the repo
npm install
npm run dev

----
**Ensure you have .env set up for Supabase keys (or use mock mode).**

