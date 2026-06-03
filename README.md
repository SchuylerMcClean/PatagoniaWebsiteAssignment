# Patagonia Adventure Tourism Website

A multi-page, highly responsive informational website dedicated to exploring the endless outdoor adventures in Patagonia, South America. This project showcases stunning regional activities—including skiing, kayaking, hiking, camping, and rock climbing—built entirely using semantic HTML5 and custom CSS3.

## 🚀 Features

* **Comprehensive Content:** Seven dedicated activity and informational pages detailing world-class outdoor experiences in the Patagonia region.
* **Dynamic UI/UX:** Custom hover mechanics, interactive elements, and smooth transitions built into the global stylesheet to create an engaging, responsive user experience.
* **Optimized & Diverse Media:** Utilizes a mix of modern, high-compression asset formats (`.webp`, `.avif`) and standard images (`.jpg`, `.png`) to balance rich visual storytelling with optimized loading times.
* **Custom 404 Error Page:** A tailored fallback page to handle broken links gracefully and keep users immersed in the site's design.

---

## 📂 Repository Structure

The project features a clean, flat architecture where individual HTML modules interface directly with a centralized stylesheet and targeted media assets:

```text
├── 404.html                      # Custom error landing page
├── README.md                     # Project documentation
├── home.html                     # Website main landing page
├── webstyle.css                  # Centralized stylesheet managing layouts & hover mechanics
│
├── [Activity & Informational Pages]
│   ├── one.html                  # Exploration / Activity page 1
│   ├── two.html                  # Exploration / Activity page 2
│   ├── three.html                # Exploration / Activity page 3
│   ├── four.html                 # Exploration / Activity page 4
│   ├── five.html                 # Exploration / Activity page 5
│   ├── six.html                  # Exploration / Activity page 6
│   └── seven.html                # Exploration / Activity page 7
│
└── [Media Assets]
    ├── activities-background.avif
    ├── camping-activities.jpg
    ├── climbing-preview.webp
    ├── hiking-activities.jpg
    ├── hiking-preview.webp
    ├── kayak-activities.jpg
    ├── mount-fitz-roy.png
    ├── patagonia-mountains.jpg
    ├── rockclimbing-activities.jpg
    ├── skiing-activities.jpg
    └── skiing-preview.jpg
