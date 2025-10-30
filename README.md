# Mahinda Rajapaksha College Homagama
## Smart Board Opening Ceremony - Interactive Lamp Lighting Experience

---

## 📋 Project Overview

This is an interactive web-based application designed for the **Smart Board Opening Ceremony** at Mahinda Rajapaksha College Homagama. The ceremony features an engaging lamp-lighting experience where guests collectively illuminate 18 lamps to symbolize the commencement of the event.

### 🎯 Event Purpose
To create a memorable and interactive ceremonial experience that brings together the college community to formally inaugurate the new smart board technology integration.

---

## ✨ Features

- **Interactive Lamp Lighting**: 18 clickable lamps arranged in an aesthetic pattern
- **School-Themed Colors**: 
  - **Red (#C41E3A)** - Main heading (school colors)
  - **Gold (#D4AF37)** - Accent text (inspired by school logo)
  - **Professional Design** - Ceremonial and elegant appearance

- **Progressive Activation**: Each lamp toggles between lit and unlit states
- **Complete Ceremony Trigger**: When all 18 lamps are illuminated, the experience automatically transitions to the next phase
- **Smooth Transitions**: Fade-out animation between pages for a polished user experience
- **Responsive Design**: Optimized for display on smart boards and interactive screens

---

## 🏗️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Framework**: Bootstrap 5.2.3
- **Libraries**: jQuery 3.6.3
- **Animations**: Custom CSS animations for visual effects

---

## 📁 Project Structure

```
OilLamp/
├── index.html              # Main ceremony page with lamp grid
├── page2.html              # Next ceremony phase (to be configured)
├── style.css               # Main stylesheet
├── animation.css           # Animation effects
├── lamp.png               # Unlit lamp image
├── lamp.gif               # Lit lamp animation
├── lamptr.png             # Decorative lamp image
├── FCT.png                # Background image
└── README.md              # This file
```

---

## 🚀 How to Use

### For Event Organizers:

1. **Setup**: Open `index.html` in a web browser on your smart board display
2. **Display**: The lamp grid will appear with the school's ceremonial branding
3. **Execution**: Invite guests or dignitaries to click on the lamps in sequence
4. **Completion**: Once all 18 lamps are illuminated, the page automatically advances to the next phase

### Guest Interaction:

- Click on any lamp to light it (changes from gray to golden/animated)
- Click again to turn it off if needed
- Continue until all lamps are glowing
- Wait for automatic transition to the next phase

---

## 🎨 Design Elements

### Color Scheme (Based on School Logo)
- **Primary Red**: #C41E3A (Strong ceremonial presence)
- **Gold Accent**: #D4AF37 (Elegant and prestigious)
- **Dark Tones**: Professional and formal background
- **White Text**: High contrast and readability

### Layout
- **Header Section**: College name, ceremony title, and instructions
- **Lamp Grid**: 18 lamps arranged in organized rows
- **Animation Elements**: Circle containers for decorative effects
- **Responsive Grid**: 3-4 lamps per row for balanced visual presentation

---

## 🔧 Customization

### To Modify Lamp Count:
Edit the HTML lamp sections and update the JavaScript condition checking all 18 lamp states.

### To Change Colors:
Update the hex color values in the header section:
- College name: `color: #C41E3A`
- Ceremony title: `color: #D4AF37`

### To Change Next Page:
Update the redirect in the `vidpage()` function:
```javascript
window.location.replace("page2.html"); // Change this path
```

### To Adjust Timing:
- Transition delay: Change `3000` (3 seconds) in the `changeImage()` functions
- Fade animation: Change `1000` (1 second) in `vidpage()` function

---

## 📱 Browser Compatibility

- Chrome/Edge (Recommended for smart boards)
- Firefox
- Safari
- Mobile browsers (responsive design)

---

## 🎓 Educational Value

This interactive experience:
- Symbolizes collective effort and unity
- Creates a memorable ceremonial moment
- Engages the entire audience
- Marks the significant integration of smart board technology at the college

---

## 📝 Event Guidelines

1. **Setup Time**: 10-15 minutes before ceremony
2. **Audience**: Entire student body, faculty, and guests
3. **Duration**: 5-10 minutes for complete lamp lighting
4. **Technical Requirements**: Internet browser, projector/smart board display

---

## 🔐 Notes

- All lamp states are client-side (no server required)
- No personal data is collected
- Application runs entirely in the browser
- Fully functional offline after initial load

---

## 👥 Contact & Support

For technical support or modifications:
- Contact the IT department at Mahinda Rajapaksha College Homagama

---

## 📄 License

This project is created specifically for Mahinda Rajapaksha College Homagama Smart Board Opening Ceremony.

---

**Created for**: Smart Board Opening Ceremony 2025 
**Institution**: Mahinda Rajapaksha College Homagama  
**Event Theme**: Unity, Technology, and Progress
