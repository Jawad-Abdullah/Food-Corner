# Food Corner 🍕

**Good food. Good mood.**

🌐 **Live website:** [https://jawad-abdullah.github.io/Food-Corner/](https://jawad-abdullah.github.io/Food-Corner/)

Food Corner is a single-page restaurant website for a neighborhood food spot in Wah Cantt, Pakistan. It is built with plain HTML and CSS, with no frameworks or build tools, and showcases a menu, an about section, and an order request form.

## Features

- **Responsive single-page layout** with smooth in-page navigation (Home, Menu, About, Contact)
- **Hero section** with a tagline and a call to action
- **Menu grid** with four dishes, each with a description and price:
  | Item | Price |
  | --- | --- |
  | Garden Pizza | Rs. 1,250 |
  | Corner Burger | Rs. 850 |
  | Market Sandwich | Rs. 620 |
  | Sunday Pasta | Rs. 980 |
- **About section** describing the restaurant
- **Order request form** (name, email, menu item, quantity, order details) that emails the submission through [FormSubmit](https://formsubmit.co/)
- **Custom typography** using Google Fonts (DM Sans and Fraunces)

## Project Structure

```
Food-Corner/
├── images/                      # Image assets used by the site
├── index.html                   # Main website page
├── style.css                    # Site styles
├── report.html                  # Lab report (HTML version)
└── FoodCorner-Lab3-Report.pdf   # Lab 3 report (PDF version)
```

## Live Demo

This website is live and hosted on GitHub Pages: [https://jawad-abdullah.github.io/Food-Corner/](https://jawad-abdullah.github.io/Food-Corner/)

## Getting Started

No installation or build step is needed to run it locally.

1. Clone the repository:
   ```bash
   git clone https://github.com/Jawad-Abdullah/Food-Corner.git
   cd Food-Corner
   ```
2. Open `index.html` in any modern web browser.

You can also serve it locally, for example:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Order Form Setup

The order form posts to FormSubmit, which forwards each submission to the email address set in the form's `action` attribute in `index.html`:

```html
<form action="https://formsubmit.co/your-email@example.com" method="POST">
```

To receive orders at your own address, replace the email in that URL. On the first submission, FormSubmit sends a confirmation email that you must activate before orders are delivered.

## Built With

- HTML5
- CSS3
- [Google Fonts](https://fonts.google.com/)
- [FormSubmit](https://formsubmit.co/)

## Contact

**Jawad Abdullah**
Wah Cantt, Pakistan
📧 jawadabdullah525@gmail.com

---

© 2026 Food Corner
