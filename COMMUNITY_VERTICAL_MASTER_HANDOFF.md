# ROOTED Community — Master Handoff (Vertical Engineering Contract)

This is the binding UI ↔ Backend integration document for the Community vertical.

If UI behavior conflicts with this document → this document wins.

---

## 1. Vertical Definition

Community is ROOTED’s public discovery layer.

It exposes:
- Local vendors
- Community institutions
- Seasonal discovery
- Landmarks
- Volunteer events
- Kids-safe education

It does NOT expose:
- Procurement tools  
- Bid markets  
- Bulk procurement  
- Paid placements  
- Construction flows  
- Healthcare flows  

---

## 2. Roles & Access

### Guest
- Browse community map  
- View vendor profiles  
- View events & landmarks  

### Individual
- Save favorites  
- Join events  
- Enter Kids Mode with parental toggle  

### Vendors (Community)
- Manage vendor profile  
- Post community events  
- Post volunteer opportunities  
- Upload photos & media  

### Institutions
- Same as vendors, but aligned to community orgs  
- Cannot access RFQs in this vertical  

### Admin
- Moderate vendors, institutions, events, and landmarks  
- Approve sanctuary status  
- Approve nonprofit tags  
- Approve seasonal content  

---

## 3. Kids Mode in Community

Kids Mode must:

### SHOW:
- Parks  
- Farms  
- Animals  
- Public spaces  
- Kids-safe events  
- Simple history/heritage  

### HIDE:
- Prices  
- CTAs (“book”, “request”, “inquire”)  
- Donation/fundraising  
- Mature themes  
- Long-distance trips  
- Any content that could encourage unsupervised travel  

---

## 4. Community Categories (Specialties)

Use provider_badges with:

- FARM  
- MARKET  
- FOOD_MAKER  
- ARTISAN  
- COMMUNITY_CENTER  
- SANCTUARY  
- RESCUE  
- FAMILY_ACTIVITY  
- EDUCATIONAL_SITE  
- HERITAGE  

No category may imply political or religious identity.

---

## 5. Discovery Surfaces

Community uses:

- providers_discovery_v1  
- seasonal_featured_providers_v1  
- GEO_RULES.md (50 miles, 6–8 cards)  
- DISCOVERY_RULES.md  

No override permitted.

---

## 6. Map Rules

Kids Mode:
- Reduced marker detail  
- Safe-only landmarks  
- No adult-only categories  

Normal Mode:
- Full community markers  
- Seasonal discovery clusters  

---

## 7. Event Types (Community)

Use `event_vertical = 'COMMUNITY'`

Allowed:
- Family activities  
- Workshops  
- Classes  
- Volunteer  
- Educational events  

Not allowed:
- Contractor events  
- Healthcare events  
- Workforce or job fairs  

---

END OF HANDOFF