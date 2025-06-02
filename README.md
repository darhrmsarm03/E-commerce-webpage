
# Logtadds Shopping Page

## Overview
Welcome to the Logtadds Shopping Page! This is a simple, responsive e-commerce webpage designed to showcase a collection of jeans for the 2025 season. Built using HTML, CSS, and JavaScript, it features a sidebar menu, product grid, and subscription section, styled with the W3.CSS framework and Font Awesome icons.

## Features
- **Responsive Design**: Adapts to various screen sizes, with a sidebar menu for desktop and a collapsible menu for mobile devices.
- **Product Grid**: Displays 8 jeans products with images, prices, and "Buy Now" buttons that link to an external checkout system.
- **Interactive Elements**: Includes an accordion-style menu for product categories and hover effects for product images.
- **Subscription Section**: Allows users to input an email address for special offers and VIP treatment.
- **Footer**: Contains contact information, blog post previews, and popular tags for navigation and engagement.

## Technologies Used
- **HTML5**: Structure of the webpage.
- **CSS3**: Styling, enhanced by W3.CSS (via CDN) and a custom `project.css` file.
- **JavaScript**: Handles accordion functionality and sidebar toggle for mobile views.
- **External Libraries**:
  - W3.CSS (https://www.w3schools.com/w3css/4/w3.css)
  - Font Awesome (https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css)
  - Google Fonts (Karma font)

## Project Structure
```
logtadds-shopping-page/
├── assets/
│   └── css/
│       └── project.css        # Custom CSS styles
├── images/
│   ├── logo11.jpeg            # Logo for sidebar and header
│   ├── man-wearing-denim-jeans-1804075.jpg  # Header image
│   ├── boots-cardigan-denim-fashion-6710.jpg  # Product image
│   ├── man-in-gray-denim-jacket-leaning-on-woman-3254131.jpg  # Product & blog image
│   ├── person-wearing-distressed-denim-jeans-2225142.jpg  # Product image
│   ├── photo-of-person-wearing-white-t-shirt-and-blue-denim-jeans-4066290.jpg  # Product image
│   ├── person-in-black-denim-jeans-and-white-sneakers-3908081.jpg  # Product image
│   ├── man-sitting-on-ledge-1306248.jpg  # Product image
│   ├── two-people-wearing-rugged-jeans-1365363.jpg  # Product image
│   ├── photo-of-person-wearing-tattered-jeans-3751376.jpg  # Product & blog image
├── product.html                 # Main HTML file
├── privacy-policy.html        # Privacy policy page (not included)
├── cookie-policy.html         # Cookie policy page (not included)
├── training.html              # Tutorial training page (not included)
└── README.md                  # This file
```

## Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/logtadds-shopping-page.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd logtadds-shopping-page
   ```
3. **Open the Page**:
   - Open `product.html` in a web browser to view the page locally.
   - Ensure an internet connection for loading external resources (W3.CSS, Font Awesome, Google Fonts).

## Usage
- **Navigation**: Use the sidebar (desktop) or top menu (mobile) to explore categories like "Jeans" with a dropdown for "Fitted" items.
- **Shopping**: Browse the product grid, hover over images to reveal "Buy Now" buttons, and click to proceed to the checkout via an external link.
- **Subscription**: Enter an email in the subscription section and click "Subscribe" (note: functionality requires additional backend setup).
- **Footer Links**: Access privacy policy, cookie policy, and tutorial training pages (placeholders; implement these files as needed).

## Customization
- **Images**: Replace files in the `images/` folder with your own, ensuring filenames match those referenced in `product.html`.
- **Styles**: Modify `assets/css/project.css` to adjust colors, layouts, or other styles.
- **Products**: Update the product grid in `product.html` to add or remove items, adjusting names, prices, and image paths.
- **Checkout**: The "Buy Now" buttons link to an external service (e.g., `https://ww9.aitsafe.com`). Update the URLs and `userid` parameter to match your checkout system.

## Notes
- **External Links**: The checkout buttons use an external service; ensure the `userid=B8270502` and product links are valid for your setup.
- **Missing Files**: `privacy-policy.html`, `cookie-policy.html`, and `training.html` are referenced but not provided; create these for full functionality.
- **Subscription**: The form is static; implement a backend (e.g., Node.js, PHP) to handle email submissions.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## Credits
- **Author**: darhrmsarm
- **Images**: Sourced from various providers (ensure proper licensing for commercial use).
- **Frameworks**: W3.CSS and Font Awesome

## License
This project is licensed under the MIT License. See the `LICENSE` file for details (create one if needed).

