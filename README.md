# 🏙️ Business Directory – Local Listings Platform (Laravel)

**Business Directory** is a Laravel-based web application designed to help small towns and cities showcase local businesses, featured vendors, deals, events, and more. Ideal for local entrepreneurs, community managers, and service providers.

---

## 🔎 Key Features

- 🏪 **Business Listings** – Add shops, services, hospitals, salons, and more
- 🌟 **Featured Businesses** – Promote top businesses with special badges
- 🎁 **Deals & Offers** – List time-limited discounts from local vendors
- 📅 **Events** – Showcase upcoming local events
- 🧭 **Multi-Category Support** – Group listings by business type and tags
- 🖼️ **Media Gallery** – Add logos, banners, and photo galleries to listings
- ⏰ **Business Hours** – Set open/close times for each day
- 📍 **Location-Aware** – Include address, maps, and contact info
- 🔍 **Search & Filter** – Easily find businesses by name or category

---

## 🛠️ Built With

- **Laravel 8+**
- **PHP 7.4+**
- **MySQL / MariaDB**
- **Blade / Bootstrap**
- Optional: Vue.js or Livewire for dynamic UI

---

## 🚀 Installation Instructions

```bash
git clone https://github.com/ashvinsolanki/local-business-directory.git
cd business-directory
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

---

##License
This project is open-source and available under a custom permissive license:

Original inspiration: OfficialOzioma/business-directory
