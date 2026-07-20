# IHG Hospitality Prompt Library for Gemini Enterprise

Welcome to the **IHG Hospitality Prompt Library**! This cheat sheet provides ready-to-use prompt templates for IHG team members across various departments. 

To achieve the best results with Gemini Enterprise, follow the **PCTF Framework**:
- **P**ersona: Who Gemini should act as (e.g., *Guest Relations Director, Hotel Operations Specialist*).
- **C**ontext: Background information, constraints, or hotel property specifics.
- **T**ask: The specific action you want Gemini to perform.
- **F**ormat: The desired output style (e.g., *bulleted list, professional email, executive memo, tabular format*).

---

## 🏨 1. Hotel Operations & Guest Experience

### 1.1 VIP Guest Welcome Letter & Itinerary
```text
Role: You are the Chief Concierge at InterContinental London Park Lane.
Context: A Diamond Elite IHG One Rewards member is checking in for a 3-night anniversary stay at InterContinental London Park Lane.
Task: Write a personalized welcome letter and draft a 1-day luxury weekend itinerary highlighting local cultural spots and fine dining near Park Lane.
Format: Professional, warm letter followed by a clear, time-stamped bulleted itinerary.
```

### 1.2 Guest Service Recovery Email
```text
Role: You are the Guest Relations Manager at Kimpton Hotel Eventi in New York.
Context: A guest experienced a 45-minute delay during check-in due to a system glitch and reported noise from adjacent HVAC equipment during their stay.
Task: Draft a sincere, empathetic service recovery response. Offer 15,000 IHG One Rewards bonus points as a gesture of goodwill and explain the steps taken to resolve the HVAC noise.
Format: Polished customer service email with placeholders [Guest Name] and [Confirmation Number].
```

### 1.3 Front Desk Shift Handover Summary
```text
Role: You are an Assistant Front Office Manager at Holiday Inn Express Nashville Downtown.
Context: Here are the unstructured notes from the morning shift:
- Room 304 reported low hot water pressure; engineering notified at 10:15 AM.
- 12 late check-outs granted for IHG One Rewards Gold members.
- VIP arrival in Suite 502 (Mr. Henderson) arriving at 4:00 PM; amenity tray needed.
- Shuttle bus to airport scheduled for maintenance at 2:00 PM; temp driver covering.
Task: Synthesize these shift notes into an organized afternoon handover briefing for the evening front desk team.
Format: Categorized bulleted summary under headers: Immediate Action Items, VIP Arrivals, Maintenance & Facilities, and Staffing Notes.
```

---

## 💳 2. IHG One Rewards & Loyalty Marketing

### 2.1 Seasonal Loyalty Promotion Campaign Copy
```text
Role: You are a Senior Brand Marketer for IHG One Rewards.
Context: We are launching a "Double Points + Stay 3 Nights, Get 1 Free" summer promotion targeting corporate business travelers across Holiday Inn and Crowne Plaza properties.
Task: Write 3 variations of campaign copy:
1. Email subject lines and body copy for existing IHG One Rewards members.
2. A short push notification message (<120 characters) for the IHG mobile app.
3. Social media teaser copy for LinkedIn and Instagram.
Format: Segmented by channel, using an inspiring, action-oriented tone emphasizing travel rewards.
```

### 2.2 Loyalty Benefits Comparison Table
```text
Role: You are a Loyalty Program Specialist at IHG Corporate.
Context: Front desk agents need a quick-reference guide explaining member benefits across Club Member, Silver Elite, Gold Elite, Platinum Elite, and Diamond Elite tiers.
Task: Create a clear comparison table listing key perks (Bonus Points, Late Check-out, Complimentary Upgrades, Welcome Amenities, Rollover Nights).
Format: Markdown table with column headers for Tier Name, Bonus Point Multiplier, Key Perks, and Qualification Criteria.
```

---

## 🏢 3. Franchise Support & Hotel Development

### 3.1 Franchise Owner Onboarding FAQ Brief
```text
Role: You are a Franchise Operations Director at IHG Hotels & Resorts.
Context: A new franchise owner is converting an independent hotel into a Crowne Plaza property. They have questions about brand standards, PMS integration, and staff training requirements.
Task: Draft a comprehensive FAQ response outlining the top 5 steps for brand integration, required technology setups, and IHG University training timelines.
Format: Q&A format with bolded questions and clear, numbered procedural steps.
```

### 3.2 Property Performance Summary for Asset Managers
```text
Role: You are a Hospitality Asset Analyst at IHG Corporate.
Context: Reviewing quarterly operational metrics for a portfolio of 10 Holiday Inn Express properties: Average Occupancy: 74.5%, ADR: $148.50, RevPAR: $110.63, Guest Satisfaction Score: 88.2/100.
Task: Provide an executive briefing analyzing performance highlights, identifying 2 key growth opportunities (e.g., boosting weekday corporate bookings), and suggesting cost-efficiency measures for F&B operations.
Format: Executive memo with Executive Summary, Metric Highlights, Strategic Recommendations, and Next Steps.
```

---

## 👥 4. Human Resources & Staff Training

### 4.1 Housekeeping SOP Training Quick-Guide
```text
Role: You are an IHG Regional Learning & Development Specialist.
Context: Training new housekeeping associates on IHG Clean Promise standards across Hotel Indigo properties.
Task: Create a step-by-step checklist for deep-cleaning guest rooms between stays, focusing on high-touch surfaces, bathroom sanitization, and eco-friendly linen practices.
Format: Easy-to-read checklist grouped by room zones (Entryway, Bedroom, Bathroom, Balcony).
```

### 4.2 Employee Recognition Announcement
```text
Role: You are a Hotel General Manager at Hotel Indigo Atlanta Midtown.
Context: Recognizing Maria Santos (Executive Housekeeper) as "Employee of the Quarter" for achieving a 98% room cleanliness score and leading community sustainability initiatives.
Task: Write a warm, inspiring internal announcement to be posted in the staff lounge and sent via employee newsletter.
Format: Engaging announcement with a catchy headline, accomplishment summary, and quotes celebrating team dedication.
```

---

## 💻 5. Corporate Strategy & IT Operations

### 5.1 Technology Incident Communication (Internal IT)
```text
Role: You are an IT Service Desk Lead at IHG Global Technology.
Context: The central reservation system (CRS) experienced a 20-minute intermittent latency issue affecting hotel check-ins between 14:00 EST and 14:20 EST. The issue has been fully resolved.
Task: Draft an incident report email to Hotel General Managers and Front Desk Managers explaining the cause (database index re-balancing), resolution, and confirming all reservations are synced.
Format: Standard IT Incident Template (Incident Summary, Impact, Root Cause, Status, Preventive Measures).
```

### 5.2 Sustainable Hospitality Initiative Proposal
```text
Role: You are a Sustainability Manager at IHG Corporate.
Context: Preparing a business proposal for expanding single-use plastic elimination (bulk amenities, digital keys, zero-waste food prep) across 50 regional Staybridge Suites and Candlewood Suites properties.
Task: Draft a 1-page executive pitch outlining financial ROI, carbon footprint reduction, guest brand perception benefits, and implementation timeline over 6 months.
Format: Bulleted proposal with clear headers and measurable target KPIs.
```

---

## 🎨 6. Creative & Brand Media Generation (Imagen 3 & Veo 3.1 Prompts)

### 6.1 Ultra-Realistic Luxury Resort Imagery (Text-to-Image / Imagen 3)
```text
Photorealistic 8k architectural photograph of an overwater bungalow villa at InterContinental Bora Bora Resort at sunset. Warm golden hour lighting casting long soft shadows across polished teak wood decking. Modern infinity pool blending into turquoise lagoon waters. Shallow depth of field, f/2.8 lens aperture, 35mm Hasselblad camera perspective, cinematic color grading with rich blue and warm orange tones, high detail on water ripples and palm leaf texture.
```

### 6.2 Boutique Interior Design & Mood Lighting (Text-to-Image / Imagen 3)
```text
Architectural shot of a vibrant luxury lounge bar at Kimpton Hotel Eventi in New York. Industrial chic aesthetic with exposed brickwork, custom plush velvet seating in deep emerald green and bronze tones, warm Edison bulb pendant lighting, ambient bar glow. Professional architectural photography style, 24mm wide-angle lens, perfectly straight vertical lines, soft fill light, high resolution, filmic grain texture.
```

### 6.3 Cinematic Time-Lapse Lobby Video (Text-to-Video / Veo 3.1)
```text
A high-resolution cinematic slow-motion video of a luxury InterContinental hotel lobby entrance at dusk. Smooth camera motion: a gradual forward dolly shot tracking guests arriving in formal attire. Warm interior lighting with a grand crystal chandelier reflecting on polished marble floors. Volumetric evening light streaming through floor-to-ceiling glass windows, realistic motion blur, 4k ultra-HD quality, 24fps film aesthetic.
```

### 6.4 Signature Mixology & Culinary Close-Up Video (Text-to-Video / Veo 3.1)
```text
Cinematic macro close-up video of an expert mixologist crafting a signature smoked cocktail at a Regent Hotels rooftop sky bar at night. Slow-motion 120fps camera move: liquid pour over a crystal clear sphere ice block, subtle smoke rising from wood chips, city skyline bokeh lights blurred gracefully in the background, sharp focus on water droplets on the crystal glass, dynamic warm lighting.
```
