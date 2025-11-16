# Health System - Hospital Management System

Modern health service system with responsive and user-friendly interface for hospitals.

## Folder Structure

```text
health-system/
├── css/
│   └── style.css          # Main stylesheet with modern and responsive design
├── js/
│   └── main.js            # Main JavaScript with common functions
├── assets/
│   └── images/            # Folder for images and assets
├── index.html             # Homepage with navbar
├── pendaftaran.html       # Patient registration form
├── pemeriksaan.html       # Doctor examination form
├── farmasi.html           # Pharmacy & prescription form
├── pembayaran.html        # Payment form
└── README.md              # Project documentation
```

## Design Features

- **Modern & Clean**: Modern design with primary color #4200FF
- **Responsive**: Fully responsive for desktop, tablet, and mobile
- **Compact**: More compact design for desktop
- **Icons**: Using Lucide Icons for better icons
- **Typography**: Poppins font for better readability
- **Glass Effect**: Glass card effect with backdrop-filter
- **Smooth Animations**: Smooth transitions and animations

## Technologies Used

- **HTML5**: Semantic structure
- **CSS3**: Custom CSS with CSS Variables
- **JavaScript**: Vanilla JavaScript (ES6+)
- **Lucide Icons**: Modern icon library
- **Google Fonts**: Poppins font family

## Pages

1. **index.html** - Homepage with service information and process
2. **pendaftaran.html** - New patient registration form
3. **pemeriksaan.html** - Doctor examination form
4. **farmasi.html** - Pharmacy and prescription form
5. **pembayaran.html** - Payment form with automatic calculation

## Main Features

- Responsive navbar with mobile menu
- Form validation
- Automatic cost calculation
- Toast notifications
- Smooth scrolling
- Icon integration with Lucide
- Responsive grid system
- Modern card components

## How to Use

### Online Access (Fastest Way)

**Open directly through the following link:**
**[https://sik-xyz.vercel.app/](https://sik-xyz.vercel.app/)**

Or copy and open in browser: `https://sik-xyz.vercel.app/`

---

### Running with Live Server (VS Code)

1. **Install Live Server Extension in VS Code:**

   - Open VS Code
   - Click on the Extensions icon (or press `Ctrl+Shift+X` / `Cmd+Shift+X`)
   - Search for "Live Server" by Ritwick Dey
   - Click "Install" to install the extension

2. **Running the Project:**

   - Open the project folder in VS Code
   - Right-click on the `index.html` file
   - Select "Open with Live Server" from the context menu
   - Or click the "Go Live" button in the status bar at the bottom of VS Code
   - Browser will automatically open with URL `http://127.0.0.1:5500` or another port

3. **Alternative - Open Directly in Browser:**
   - Open `index.html` in browser to view the homepage
   - Navigate through the navbar to access various forms
   - All forms are integrated with JavaScript for validation and calculation
   - Responsive design will adjust to screen size

## Customization

Colors and styling can be changed through CSS Variables in `css/style.css`:

```css
:root {
  --primary-color: #4200ff;
  --primary-hover: #3500cc;
  --text-primary: #404040;
  --text-secondary: #9d9d9d;
  /* ... */
}
```

## Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2025 Health System - General Hospital
