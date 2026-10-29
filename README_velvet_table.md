# Velvet Table --- Fine Dining Website

Velvet Table is a fine-dining restaurant website concept built with HTML
and CSS. It presents the restaurant's signature dish, menu, dining
experience, guest reviews, and a table reservation form in an elegant
dark-and-gold design.

## Features

-   Sticky navigation with links to Home, Menu, Experience, Reviews, and
    Reserve
-   Hero section with a restaurant-themed background image
-   Restaurant philosophy and introduction section
-   Chef's signature dish feature: Black Truffle Tagliatelle
-   Menu organized into Starters, Main Course, and Desserts
-   Dish descriptions and sample prices in Indian rupees
-   Dining experience section highlighting ambience, cuisine, and
    service
-   Guest review cards
-   Reservation section with contact details and form fields for name,
    email, date, time, number of guests, and special requests
-   Footer with navigation links
-   Responsive layout using CSS Grid, Flexbox, and media queries
-   Hover effects, focus styling, and smooth scrolling

## Technologies Used

-   HTML5
-   CSS3
-   External restaurant background image from Unsplash

## Project Files

Keep the HTML, CSS, and image files together in the same folder:

``` text
project-folder/
├── 20restaurent.html
├── 20restaurent.css
├── pasta.jpg
└── restaurent.jpg
```

The HTML file links to the stylesheet using:

``` html
<link rel="stylesheet" href="20restaurent.css">
```

The HTML references `pasta.jpg` for the chef's signature dish and
`restaurent.jpg` for the dining-experience image. Make sure these image
files exist in the project folder and that their names match the HTML
exactly. The hero background image is loaded from an external Unsplash
URL in the CSS.

## How to Run Locally

1.  Save `20restaurent.html` and `20restaurent.css` in the same folder.
2.  Add the required local image files (`pasta.jpg` and
    `restaurent.jpg`) to that folder.
3.  Open `20restaurent.html` in a web browser.

You can also open the project folder in Visual Studio Code and use a
local preview extension.

## Publishing with GitHub Pages

1.  Upload the HTML, CSS, and required local images to your GitHub
    repository.
2.  Open **Settings → Pages** in the repository.
3.  Under **Build and deployment**, select **Deploy from a branch**.
4.  Choose the `main` branch and the `/ (root)` folder, then save.
5.  After deployment completes, open the published URL shown in the
    Pages settings.

GitHub Pages typically serves a root-level `index.html` as the default
homepage. To make this restaurant website the default page, rename
`20restaurent.html` to `index.html` and keep the stylesheet link set to
`20restaurent.css`. Otherwise, the page may be accessible using its
individual HTML-file URL.

## Important Notes

-   This is a static front-end project. The reservation form is a visual
    form and is not connected to a booking service or backend.
-   Contact information, restaurant address, menu items, prices, and
    guest reviews are example content and should be verified before
    real-world use.
-   The page's local images must be uploaded to GitHub for them to
    appear after deployment.
-   The hero background image depends on an internet connection because
    it is loaded from Unsplash.

## Author

Created as an HTML and CSS web development project.
