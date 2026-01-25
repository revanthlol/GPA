# GPA Calculator 🎓

A modern, responsive GPA (Grade Point Average) calculator with support for both SGPA (Semester GPA) and CGPA (Cumulative GPA) calculations. Features a clean, mobile-friendly interface with dark/light theme support.

## ✨ Features

- **Subject Management**: Add unlimited subjects with name, credits, and grade points
- **Dual GPA Display**: Displays both SGPA and CGPA (both show the same calculated GPA for the current semester)
- **Real-time Calculation**: Instant GPA updates as you add or remove subjects
- **Dark/Light Theme**: Toggle between themes with persistent preference storage
- **Responsive Design**: Optimized for mobile, tablet, and desktop devices
- **Input Validation**: Ensures valid credit and point values (0-10 scale)
- **Toast Notifications**: Visual feedback for user actions
- **Confirmation Dialogs**: Prevent accidental data loss when resetting
- **Clean UI**: Modern design with smooth animations and transitions

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No installation or dependencies required!

### Usage

1. **Open the Application**: Simply open `index.html` in your web browser
2. **Add Subjects**:
   - Enter the subject name (optional - defaults to "Subject N")
   - Input the credit hours for the subject
   - Enter the grade points (0-10 scale)
   - Click "Add Subject" or press Enter
3. **View Your Subjects**: All added subjects appear in the course list table
4. **Calculate GPA**: Click the "Calculate" button to compute your SGPA/CGPA
5. **Remove Subjects**: Click the × button next to any subject to delete it
6. **Reset**: Use the Reset button to clear all data (with confirmation)

## 📊 GPA Calculation

The calculator uses the standard weighted average formula:

```
GPA = Σ(Credit × Points) / Σ(Credits)
```

Where:
- **Credit**: The credit hours/units for each subject
- **Points**: The grade points earned (typically 0-10 scale)

## 🎨 Theme Support

Toggle between light and dark themes using the button in the top-right corner. Your preference is automatically saved and restored on future visits.

- **Light Theme**: Clean white background with indigo accents
- **Dark Theme**: Elegant slate dark background with softer colors

## 💡 Technical Details

### Built With

- **Pure HTML/CSS/JavaScript**: No frameworks or libraries required
- **CSS Custom Properties**: For theming and easy customization
- **LocalStorage API**: For theme persistence
- **Responsive Grid Layout**: Mobile-first design approach
- **Google Fonts**: Inter font family for modern typography

### Browser Compatibility

Works on all modern browsers that support CSS Grid, CSS Custom Properties, and ES6 JavaScript.

### Key Features Implementation

- **Responsive Layout**: CSS Grid and Flexbox for adaptive design
- **Semantic HTML**: Proper HTML structure with labeled form inputs
- **Smooth Animations**: CSS transitions and keyframe animations
- **Mobile Optimizations**: Touch-friendly buttons, optimized viewport settings
- **Input Modes**: Decimal keyboard for numeric inputs on mobile

## 📱 Mobile Experience

The calculator is fully optimized for mobile devices with:
- Touch-optimized buttons and inputs
- Adaptive grid layouts for smaller screens
- No horizontal scrolling
- Native decimal keyboard for number inputs
- Disabled user scaling for consistent experience

## 🔧 Customization

You can easily customize the calculator by modifying the CSS variables in the `:root` selector:

```css
:root {
    --primary: #6366f1;        /* Primary color */
    --bg-body: #f3f4f6;        /* Body background */
    --bg-card: #ffffff;        /* Card background */
    --text-main: #111827;      /* Main text color */
    --radius: 16px;            /* Border radius */
    /* ... and more */
}
```

## 📝 Example

1. Add "Mathematics" with 4 credits and 9.0 points
2. Add "Physics" with 3 credits and 8.5 points
3. Add "Chemistry" with 3 credits and 9.5 points
4. Click Calculate

**Result**: GPA = (4×9.0 + 3×8.5 + 3×9.5) / (4+3+3) = 8.95

## 🤝 Contributing

This is a single-file application. Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests with improvements

## 📄 License

This project is open source and available for educational and personal use.

## 🌟 Support

If you find this calculator helpful, consider giving it a star ⭐!

---

**Note**: This calculator uses the 10-point GPA scale. If your institution uses a different scale (e.g., 4.0 scale), you may need to convert the grade points accordingly.
