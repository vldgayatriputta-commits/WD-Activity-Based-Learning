# Dr.RVR NRIIT --- College Website

A front-end college website concept for Dr.RVR NRIIT, Aagiripalli,
created using HTML and CSS. The page brings together institutional
information, academics, campus facilities, announcements, a photo
gallery, and an enquiry form in one layout.

## Features

-   Header with college branding and navigation links
-   Hero section with a campus background image and introductory message
-   Quick links for Admissions, Academics, Campus, and Announcements
-   About section describing the institution
-   Highlight/statistics strip
-   Academics section with department and learning-area cards
-   Facilities section featuring the library, laboratories, technology,
    sports, and student activities
-   News and announcements cards
-   Campus photo gallery
-   Contact details and enquiry form layout
-   Footer with quick links and social links
-   Responsive layout for tablet and mobile screens
-   CSS Grid, Flexbox, hover effects, smooth scrolling, and media
    queries

## Technologies Used

-   HTML5
-   CSS3

## Project Files

Keep the HTML, CSS, and image files together in the same project folder:

``` text
project-folder/
├── 2collegeadmission.html
├── 2collegeadmission.css
├── nri logo.jpg
├── campus.jpg
├── library.jpg
├── campus life.jpg
├── staff.jpg
└── labs.jpg
```

The image filenames above match the references in the supplied code. If
your actual filenames differ, update the `src` attributes in the HTML
and the `url(...)` path in the CSS.

The HTML file links to the stylesheet with:

``` html
<link rel="stylesheet" href="2collegeadmission.css">
```

The CSS uses `campus.jpg` as the hero background image.

## How to Run

1.  Save the HTML and CSS files in the same folder.
2.  Make sure the referenced images are in that folder too.
3.  Open `2collegeadmission.html` in a web browser, or open the folder
    in Visual Studio Code and use a local preview extension.

## Important Notes

-   This is a static front-end project. It does not include a backend or
    database.
-   The enquiry form is a visual form layout; the supplied code does not
    connect it to a service that sends messages.
-   Several navigation and social links use `#` placeholders and need
    real destinations if you want them to navigate externally.
-   The phone number and email shown in the contact section should be
    verified or replaced with official contact information before
    publishing.
-   The college-related text and page content are presented as website
    content in this project; verify institutional details before using
    the page as an official site.

## Customization Ideas

-   Replace sample text and placeholder links with verified information.
-   Add working destinations for the Student Portal, Faculty Portal, and
    social media links.
-   Connect the enquiry form to a backend or form service if submissions
    are required.
-   Check that all image files are committed to the repository so they
    display after deployment.

## Author

Created as an HTML and CSS web development project.
