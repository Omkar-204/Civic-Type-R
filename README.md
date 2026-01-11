# Honda Civic Type R Experience Website

A front-end web development project dedicated to the Honda Civic Type R. This multi-page website allows users to explore the car's history, customize their dream vehicle, and book services or test drives using interactive forms.


## ℹ️ About
This website acts as a comprehensive portal for Honda enthusiasts. It covers the evolution of the Civic Type R from the EK9 generation to the modern FL5. Beyond informational content, it implements functional forms for user interaction, including a booking system with JavaScript validation and a customization tool for selecting car parts and colors.

## ✨ Features

### 1. Home & History (`exp 1.html`)
* **Historical Timeline:** Detailed sections on the EK9, Premier Edition, Mugen Concept, FK8, and FL5 generations.
* **Multimedia Integration:** Embedded audio (`typer .mp3`) for engine sounds and video (`HONDA CIVIC TYPE R .mp4`) for promotional footage.
* **Specifications Table:** A comparison table displaying engine specs and horsepower across different generations.
* **Navigation:** Links to Test Drive, Service, and Customization pages.

### 2. Test Drive Booking (`form1.html`)
* **Form Validation:** Uses JavaScript (Regex) to ensure:
    * Names contain only alphabets.
    * Emails are valid Gmail addresses.
    * Phone numbers are exactly 10 digits.
    * Dates are in `YYYY-MM-DD` format and not in the past.
    * Time is in 24-hour format.
* **Styling:** Custom background image and semi-transparent form container.

### 3. Car Customization (`FORM3.HTML`)
* **Configurator:** Dropdown menus to select Exterior Color, Wheel Style, Body Kits, Interior Seats, and Performance Tunes.
* **External Styling:** Linked to `mystyle.css` for a consistent color theme (Red/Black/White) matching the Honda Type R brand identity.

### 4. Service Appointment (`form 2.html`)
* **Service Scheduling:** A dedicated form for current owners to book maintenance (Oil Change, Alignment, Diagnostics).
* **Design:** Distinct blue color scheme to differentiate the service department from the sales pages.

## 💻 Technologies Used
* **HTML5:** Semantic structure (Header, Footer, Section, Audio, Video).
* **CSS3:**
    * External stylesheet (`mystyle.css`) for the customization page.
    * Internal/Inline styles for gradients and layouts on the home and booking pages.
* **JavaScript:** Client-side validation for the Test Drive form.

## 📂 File Structure
* `exp 1.html`: **Main Landing Page** (Start here).
* `form1.html`: Test Drive Booking Form.
* `form 2.html`: Service Appointment Form.
* `FORM3.HTML`: Car Customization Page.
* `mystyle.css`: Stylesheet for the customization page.
* **Media Assets:**
    * `typer .mp3`: Audio file.
    * `HONDA CIVIC TYPE R .mp4`: Video file.
    * `1.jpg`, `2.jpg`, `3.jpg`: Car images used in the history section.

## 🚀 How to Run
1.  Download all project files.
2.  Ensure all images (`.jpg`), audio (`.mp3`), and video (`.mp4`) files are in the same folder as the `.html` files.
3.  Open **`exp 1.html`** in any modern web browser (Chrome, Edge, Firefox).
4.  Navigate through the website using the menu links in the header.

---
*Created for educational purposes.*
