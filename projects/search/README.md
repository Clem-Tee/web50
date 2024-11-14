
Google Search Clone - CS50 Web Programming Project

Welcome to the **Google Search Clone** project! This project replicates Google's search interface, including its image search, advanced search, and unique design features. This README provides an overview, installation steps, features, and demonstrations.

📍 **Project Repository**: [web50](https://github.com/Clem-Tee/web50)

## 📖 Project Overview

This project is part of **Harvard's CS50 Web Programming** course. The primary goal is to create a functional and aesthetically pleasing front-end interface for **Google Search** using HTML and CSS.

### Built With:
- **HTML** & **CSS** for UI design.
- **JavaScript** for client-side functionality.
- **Django** (CS50 course introduction).

## 🚀 Features

- **Google Search Interface**: A custom-designed search input and button similar to Google’s, featuring a centered layout, rounded corners, and smooth animations.
- **Image Search Page**: Allows users to search images directly from a dedicated search form.
- **Advanced Search Page**: Four advanced search input fields to fine-tune search queries.
- **"I'm Feeling Lucky" Button**: Redirects users to the top search result for their query.
- **Responsive Layout**: Optimized for both desktop and mobile viewing.

## 📂 Project Structure

```plaintext
web50/
└── projects/
    └── search/
        ├── pages/
        │   ├── index.html            # Google Search Page
        │   ├── imagesearch.html      # Google Image Search Page
        │   ├── advancedsearch.html   # Google Advanced Search Page
        ├── css/
        │   └── styles.css            # Custom CSS Styling
        └── README.md                 # Project Documentation
```

## 🔧 Installation and Setup

### Clone the repository:
```bash
git clone https://github.com/Clem-Tee/web50.git
cd web50/projects/search
python3 -m http.server 8000
```
**Open `index.html` in your preferred browser:**

## 💻 Usage

### Running the Search Page
1. Open `index.html`.
2. Enter a query into the search bar and click **"Google Search"**.
3. Use **"I'm Feeling Lucky"** to be redirected to the top result.

### Running the Image Search
1. Navigate to **Image Search** via the link on the upper-right of the Search Page.
2. Enter a query and click **Search Images**.

### Running the Advanced Search
1. Navigate to **Advanced Search** via the link on the upper-right of the Search Page.
2. Fill out any combination of advanced query fields.
3. Click **Advanced Search**.

---

## 📝 Project Requirements

The following requirements are met:

- [x] **Three main pages**: Search, Image Search, and Advanced Search.
- [x] **Custom search forms** with GET parameters compatible with Google Search.
- [x] **Advanced search form** with multi-field functionality.
- [x] **Stylized and responsive design** similar to Google’s.

## 🧑‍💻 Developer Notes

This project utilizes basic **HTML forms**, **CSS animations**, and **GET requests**, and is structured to support further development if desired.

> ✨ **Future Enhancements**:
> - Add JavaScript for dynamic feedback.
> - Implement CSS transitions for a smoother UI.

---

## 🤝 Connect

For any inquiries, suggestions, or collaboration requests, please contact me at [Clem-Tee GitHub](https://github.com/Clem-Tee).

---

**Enjoy exploring the Google Search Clone Project!**
