# Dr.RVR NRIIT FEST 2026 --- College Fest Website

A college fest website concept for **Dr.RVR NRIIT FEST 2026**, built
using HTML and CSS. The page promotes the fest and presents its
schedule, guests, games and activities, food stalls, DJ night,
highlights, and contact information.

## Features

-   Navigation bar with links to the main sections
-   Hero section introducing the fest with a background image
-   About section built around "Celebrate • Connect • Create"
-   Event schedule table with times, events, and locations
-   Special guests and performer cards with images
-   Games and activities section
-   Food court, creative stalls, and fun stalls section
-   DJ Night promotional section
-   Fest highlights
-   Venue and contact information
-   Registration-of-interest form with name, email, department, and
    message fields
-   Footer with fest branding and copyright text
-   Responsive navigation and layout for smaller screens
-   CSS Flexbox, hover effects, transitions, animation, pseudo-elements,
    and media queries

## Technologies Used

-   HTML5
-   CSS3

## Project Files

Keep the HTML and CSS files in the same folder, along with the local
guest images referenced in the HTML:

``` text
project-folder/
├── 26fest.html
├── 26fest.css
├── chief guest.jpg
├── satish.jpg
└── Rahman.jpg
```

The HTML file links to the stylesheet with:

``` html
<link rel="stylesheet" href="26fest.css">
```

The CSS loads some background images from external URLs. An internet
connection is needed for those backgrounds to appear. Make sure the
local image filenames match the `src` values in the HTML exactly.

## How to Run Locally

1.  Save the HTML and CSS files in the same folder.
2.  Place `chief guest.jpg`, `satish.jpg`, and `Rahman.jpg` in that
    folder.
3.  Open the HTML file in a web browser, or open the folder in Visual
    Studio Code and use a local preview extension.

## Publish with GitHub Pages

1.  Upload the HTML, CSS, and local image files to your GitHub
    repository.
2.  Open **Settings → Pages**.
3.  Under **Build and deployment**, choose **Deploy from a branch**.
4.  Select the `main` branch and the `/ (root)` folder, then save.
5.  Wait for deployment and open the URL shown in the Pages settings.

GitHub Pages typically uses a root-level `index.html` as the default
homepage. To make this fest page the repository homepage, rename the
HTML file to `index.html` and ensure the CSS link still points to
`26fest.css`. Otherwise, the page may be accessed using its individual
HTML filename.

## Important Notes

-   This is a static front-end project; it does not include a backend or
    database.
-   The registration form is a visual form and is not connected to a
    service that stores or sends submissions.
-   The displayed date, guest details, contact information, schedule,
    and event information are example content. Verify all details before
    presenting the page as an official event website.
-   The contact number is a placeholder (`+91 XXXXX XXXXX`).
-   Some navigation links in the supplied HTML use paths such as
    `Schedule`, `guests`, `activities`, and `dj` rather than section
    anchors. For in-page navigation, use matching IDs such as
    `#schedule`, `#guests`, `#activities`, and `#dj`.

## Author

Created as an HTML and CSS web development project.
