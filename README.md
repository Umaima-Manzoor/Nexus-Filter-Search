# TeamFlow – Dynamic Team Filtering & Search System

A fully responsive team directory with real-time search and filtering by role, name, and skills. Built with HTML, CSS, and vanilla JavaScript.

<br>

## 📋 Task Requirements – Fully Fulfilled

| Requirement | Status |
|-------------|--------|
| JSON data with name, role, skills/expertise | ✅ |
| Search by name, role, and skills | ✅ |
| Category filtering with buttons | ✅ |
| Combined search + filter | ✅ |
| Grid/card layout | ✅ |
| Empty state with message | ✅ |
| Smooth transitions when filtering | ✅ |
| Responsive design | ✅ |
| Debounce search input (advanced) | ✅ |
| Reset/clear filter button (advanced) | ✅ |

<br>

## 🛠️ Technologies Used

- **HTML5** – Semantic markup
- **CSS3** – Flexbox, CSS Grid, Custom Properties, Transitions
- **Vanilla JavaScript** – Fetch API, DOM manipulation, Debouncing
- **Font Awesome 6** – Icons
- **Google Fonts** – Inter

<br>

## 📁 Project Structure
```
TeamFlow/
├── index.html # Main HTML page
├── script.js # Fetch, render, search, filter logic
├── styles.css # Mobile-first CSS with responsive design
├── team.json # Team member data with skills
├── README.md # This file
└── Screenshots/ # Screenshots of the working system
    ├── desktop-view.png
    ├── mobile-view.png
    ├── search-working.png
    └── filter-working.png
```


<br>

## 🧩 Key Features

### Search Functionality
- **Search by Name** – Type any name to filter results instantly.
- **Search by Role** – Type "Developer" to see all developers.
- **Search by Skills** – Type "React" to find members with React skills.
- **Debounced Input** – Search updates after 300ms of typing to improve performance.

<br>

### Category Filtering
- **Role-Based Filtering** – Click any role button to filter members.
- **Dynamic Buttons** – Buttons are generated from unique roles in the data.
- **Combined Filtering** – Search and filter work together.

<br>

### User Experience
- **Results Count** – Shows how many members match your search.
- **Clear Filters Button** – Reset all filters with one click.
- **Empty State** – Friendly message when no results are found.
- **Smooth Animations** – Cards fade in and hover with smooth transitions.

<br>

### Responsive Design
| Screen Size | Grid Columns |
|-------------|--------------|
| Mobile (< 768px) | 1 column |
| Tablet (≥ 768px) | 2 columns |
| Desktop (≥ 1024px) | 3 columns |

<br>

## 🧪 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Umaima-Manzoor/Nexus-Filter-Search.git
   cd Nexus-Filter-Search
   ```

2. **Open the project**
- Use a local development server (e.g., VS Code Live Server)
- Note: Due to CORS restrictions, opening the file directly may block fetching team.json. Use a local server for best results.

3. **No dependencies or build tools required** – it just works.

<br>

## 📸 Screenshots

*Screenshots are included in the submission ZIP file.*

<br>

## 👩‍💻 Author

**Umaima Manzoor**  
[GitHub](https://github.com/Umaima-Manzoor/)

<br>

## 📄 License

MIT
