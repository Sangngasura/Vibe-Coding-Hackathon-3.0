
# 🌍 FoodLink Kenya

**Turning Surplus into Hope.**  
FoodLink Kenya is a digital agricultural marketplace designed to fight hunger and food waste in Kenya by directly connecting **farmers**, **buyers (organizations, schools, NGOs)**, and **drivers**.  

Our goal is simple:  
👉 Empower farmers with income opportunities  
👉 Ensure organizations access affordable food  
👉 Reduce post-harvest losses  
👉 Improve logistics efficiency

---

## 🚀 Features

- **Role-based Marketplaces**
  - 👩‍🌾 Farmers → Post surplus produce, edit/manage listings, see order requests.
  - 🏢 Organizations → Browse farmer surplus, place bulk orders, secure payments.
  - 🚚 Drivers → Register and view logistics jobs.
  - 🛠️ Admin → Manage all orders, approve payments, oversee chats.

- **Order Lifecycle**
  1. Farmer posts surplus → Organization places demand.
  2. Buyer specifies quantity and makes secure payment (M-Pesa / Card).
  3. Farmer marks “Released”.
  4. Admin approves & assigns logistics.
  5. Driver delivers → Buyer marks “Received”.

- **Payments**
  - M-Pesa (enter phone number).
  - Card (enter card details).
  - Linked securely to orders in `localStorage`.

- **Chats**
  - In-app messaging between Farmer ↔ Organization.
  - Admin visibility for transparency.

- **Auto Inventory Updates**
  - Buyer specifies quantity → reduces stock automatically.
  - Post removed when stock hits zero.

- **Mobile-First Design**
  - Clean, responsive UI built with HTML, CSS, and vanilla JS.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Data Storage:** `localStorage` (for prototype)  
- **Payments:** M-Pesa (stubbed integration), Card input forms  
- **Future Expansion:** Firebase / Airtable + AI Matching (see Pitch Deck)

---

## 📂 Project Structure

```
FoodLink-Kenya/
│
├── index.html                # Landing page
├── farmer-portal.html        # Farmer dashboard
├── buyer-portal.html         # Buyer dashboard
├── driver-portal.html        # Driver dashboard
├── admin.html                # Admin dashboard
├── admin-login.html          # Admin login
├── register-farmer.html      # Farmer login/signup
├── register-buyer.html       # Buyer login/signup
├── register-driver.html      # Driver login/signup
│
├── css/
│   └── styles.css            # Global stylesheet
│
├── js/
│   └── script.js             # Main app logic
│
└── README.md
```

---

## 📊 Impact (From Pitch Deck)

- **30–40%** of Kenya’s harvests are wasted due to poor distribution.  
- Millions go hungry while food rots in farms.  
- FoodLink Kenya provides a **dual impact**:  
  - Prevent food waste.  
  - Feed vulnerable communities.  

> *“Every 10 bags of maize saved = 50 families fed.”*

---

## 🎯 Next Steps

- Scale the prototype into a hosted platform.  
- Onboard farmers, NGOs, and logistics providers.  
- Pilot within one county to validate efficiency.  
- Expand nationwide with AI-powered matching + smart logistics.  

---

## 📞 Contact

- **Website:** FoodLink Kenya (prototype)  
- **Email:** clemosang@gmail.com  
- **Pitch Deck:** [See PDF](./Pitch-Deck-FoodLink-Kenya.pdf) 

---

✊ Together, we can **cut waste, fight hunger, and build a smarter food system for Kenya.**
