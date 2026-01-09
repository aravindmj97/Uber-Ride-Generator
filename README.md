![Vercel Deploy](https://deploy-badge.vercel.app/vercel/uber-ride-generator)
# Uber-Ride-Generator
A modern single-page web app to generate Uber deep links with map-based pickup &amp; drop selection, QR codes, and shareable ride cards. Built for speed, simplicity, and accessibility.

Awesome idea—this is a very **Netlify-friendly**, viral-ready utility app. Below is a **polished GitHub description**, **name suggestions**, and a **fancy, production-grade README** you can directly paste into your repo.

---

## 🔥 App Name Suggestions

Your original name works, but here are some **more product-like options**:

1. **RideLink** *(clean & brandable)* ⭐
2. **UberLink Generator**
3. **RideQR**
4. **GoUber**
5. **DeepRide**
6. **QuickRide Links**

👉 **Recommended:** **RideLink – Uber Deep Link Generator**

---

## 📌 GitHub Repository Description (Short)

> A modern single-page web app to generate Uber deep links with map-based pickup & drop selection, QR codes, and shareable ride cards. Built for speed, simplicity, and accessibility.

---

## 📘 Fancy GitHub README

````markdown
# 🚕 RideLink – Uber Deep Link Generator

Create **one-tap Uber ride links** with map-based pickup & destination selection, QR codes, and shareable ride cards — all from a simple, accessible single-page web app.

🔗 Perfect for websites, events, hotels, elderly users, travel planners, and quick ride sharing.

---

## ✨ Features

✅ Generate **Uber Deep Links** instantly  
✅ Choose **Current Location** or **Search on Map** for pickup  
✅ Select destination via **Map Search** or **Google Maps URL**  
✅ Automatic **Latitude & Longitude extraction**  
✅ Beautiful **shareable ride card** with rounded UI  
✅ **QR Code generation** for easy scanning  
✅ **Copy Link**, **Share Link**, and **Download Card as Image**  
✅ Fully **responsive & accessible** (elder-friendly design)  
✅ Optimized for **Netlify deployment**

---

## 🧠 How It Works

1. **Pickup Location**
   - Use *Current Location* → passes `my_location`
   - Or search a place on the embedded map

2. **Destination**
   - Search directly on the map  
   - Or paste a **Google Maps link** (lat/long auto-parsed)

3. **Generate Ride**
   - App builds a valid **Uber Deep Link**
   - Preview it as a **card + QR code**

4. **Take Action**
   - 🚀 Open Uber App  
   - 📋 Copy URL  
   - 📤 Share URL  
   - 🖼️ Download QR Card for WhatsApp / Print / Web

---

## 🔗 Uber Deep Link Format Used

```text
https://m.uber.com/ul/?action=setPickup
&pickup=my_location
&dropoff[latitude]=<LAT>
&dropoff[longitude]=<LNG>
&dropoff[nickname]=<DESTINATION_NAME>
````

> When a custom pickup is selected, `pickup[latitude]` & `pickup[longitude]` are used instead of `my_location`.

---

## 🎨 UI & Accessibility

* Large touch-friendly buttons
* High-contrast colors
* Minimal steps (ideal for elderly users)
* Clean cards with rounded corners
* Modern glass / gradient inspired design

---

## 📱 Use Cases

* Hotels & Resorts (share ride links with guests)
* Event organizers
* Restaurants & Cafes
* Elder-friendly ride booking
* Travel blogs
* Personal use (send ride links to family)

---

## 🚀 Tech Stack

* **HTML / CSS / JavaScript**
* **Google Maps API**
* **Uber Deep Links**
* **QR Code Generator**
* **Netlify** (hosting & CI)

---

## 🌍 Live Demo

https://uber-ride-generator.vercel.app/

---

## 🔐 Privacy

* No user data stored
* Location used only for link generation
* No backend required

---

## 📄 License

MIT License © 2026

---

## ❤️ Built With Love

If this helped you, ⭐ the repo and share it!
