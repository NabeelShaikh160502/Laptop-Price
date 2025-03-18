# Laptop-Price

## A laptop price dataset contains multiple features that influence the cost of a laptop. Let's break it down into categorical, numerical, and derived features in detail.

### 1. Features in the Laptop Price Dataset

#### A. Categorical Features (Non-numeric, need encoding)
Brand 🏷️

Examples: Dell, HP, Lenovo, Apple, Asus, Acer, MSI, Razer, Microsoft.
Influences price based on brand reputation, quality, and demand.
Model Name

The specific model of a laptop (e.g., "MacBook Pro 16 M2", "HP Pavilion 15-eg2009tx").
Processor (CPU) 🔥

Intel: i3, i5, i7, i9, Xeon
AMD: Ryzen 3, 5, 7, 9, Threadripper
Apple: M1, M2, M3, etc.
Higher-end processors typically lead to higher laptop prices.
Graphics Card (GPU) 🎮

Integrated: Intel UHD, Iris Xe, AMD Vega.
Dedicated: NVIDIA GTX, RTX, AMD Radeon RX.
Gaming and high-performance laptops have expensive GPUs, increasing price.
Operating System 💻

Windows, macOS, Linux, ChromeOS.
macOS laptops (MacBooks) tend to be priced higher.
Laptop Type / Form Factor 🏗️

Ultrabook, Gaming, Business, Workstation, Convertible (2-in-1), Chromebook.
Storage Type 🔄

HDD (Hard Disk Drive) – Cheaper but slower.
SSD (Solid State Drive) – More expensive but faster.
Hybrid (HDD + SSD) – Mixed performance.
Touchscreen 👆

Yes/No (Touchscreen laptops usually cost more).

#### B. Numerical Features (Continuous variables)
RAM (in GB) 🔢

4GB, 8GB, 16GB, 32GB, 64GB.
More RAM means better multitasking but higher cost.
Storage Size (in GB or TB) 📦

128GB, 256GB, 512GB, 1TB, 2TB.
SSDs are more expensive than HDDs.
Screen Size (in inches) 📏
11", 13", 14", 15.6", 17".
Larger screens cost more, especially in high-resolution models.
Screen Resolution 🖥️
HD (1366×768) → Low-cost.
Full HD (1920×1080) → Standard.
2K (2560×1440) → More expensive.
4K (3840×2160) → Premium pricing.
Refresh Rate (Hz) ⏩
60Hz, 90Hz, 120Hz, 144Hz, 240Hz (Higher refresh rates increase cost).
Weight (in kg) ⚖️
Lightweight ultrabooks (≤1.5kg) → Expensive.
Heavy gaming/workstation laptops (≥2.5kg) → Moderate pricing.
Battery Life (in hours) 🔋
More battery life typically means a higher price.
Number of USB Ports 🖧
More ports = Higher price in premium models.
Laptop Release Year 📅
Newer models are priced higher.
Price (Target Variable) 💰
The dependent variable to be predicted (in INR, USD, EUR, etc.).

### 2. Derived / Feature Engineered Variables
To improve model performance, additional features can be created:

#### A. Ratio Features
Price per GB of RAM = Price / RAM
Price per GB of Storage = Price / Storage
Price per inch of Screen Size = Price / Screen Size

#### B. Performance Metrics
Processor Speed (GHz) – Extracted from CPU name.
Gaming Score – Based on GPU model & refresh rate.

### 3. Data Collection Sources
E-commerce: Amazon, Flipkart, Newegg, Best Buy.
Laptop Manufacturer Websites: Dell, HP, Apple, Asus.
Tech Review Websites: NotebookCheck, Tom’s Hardware, GSMArena.

### 4. Use Cases of the Dataset
✅ Price Prediction Model – Predict laptop prices using ML (Linear Regression, Random Forest, XGBoost, Neural Networks).
✅ Laptop Recommendation System – Suggest best laptops based on user needs.
✅ Feature Impact Analysis – Analyze what factors affect laptop prices most.
✅ Market Trends – Study laptop price trends over years.
