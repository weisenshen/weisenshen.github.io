# USAge Website - US Antarctica/Arctic Geophysical Explorations

A community hub for coordinating polar geophysics research, workshops, and activities.

## About USAge

USAge (US Antarctica / Arctic Geophysical Explorations) coordinates and documents workshops and activities of the US polar geophysics community, with strong alignment to the SCAR-INSTANT Probing the Solid Earth and its Interactions (PSE) group.

## Website Structure

- **index.html** - Homepage with mission, recent workshops, and news
- **workshops.html** - Complete workshop archive
- **news.html** - News and community updates
- **team.html** - Team members and coordinators
- **publications.html** - Workshop reports, papers, and resources
- **workshops/** - Individual workshop detail pages
  - 2024-herndon.html
  - 2022-fortcollins.html

## Making Updates

### Content Updates

Most content can be updated by editing the HTML files directly:

1. **Homepage** (`index.html`)
   - Mission statement
   - Workshop highlights
   - News preview
   - Partner links

2. **News** (`news.html`)
   - Add new announcements by copying an existing news item
   - Update dates and content

3. **Team** (`team.html`)
   - Add new team members
   - Update coordinator information

4. **Workshops** (`workshops.html` and `workshops/*.html`)
   - Add new workshops
   - Update workshop details

### Styling Updates

All styling is in `css/style.css`. Key sections:

- **Colors**: Defined in `:root` variables at the top
- **Navigation**: `.nav` classes
- **Layout**: `.content-wrapper` for main/sidebar split
- **Components**: Buttons, cards, workshop items

### Customization

#### Change Colors
Edit the CSS variables in `css/style.css`:
```css
:root {
    --primary-blue: #003366;   /* Main color */
    --accent-blue: #4da8da;    /* Accent color */
    --dark-gray: #333333;      /* Text color */
    --light-gray: #f4f4f4;     /* Background */
}
```

#### Update Logo
Replace `images/logo.svg` with your own logo file (SVG, PNG, or JPG)

#### Mailing List Form
Update the form action URL in `index.html`:
```html
<form class="signup-form" action="YOUR_FORM_URL" method="get">
```

## Technical Details

- **Framework**: Static HTML/CSS (no build process required)
- **Fonts**: Google Fonts (Montserrat + Open Sans)
- **Hosting**: GitHub Pages
- **Responsive**: Mobile-friendly design

## Support

For questions or issues:
- Email: Weisen.Shen@stonybrook.edu
- GitHub Issues: [Create an issue on your repository]

## License

This website is maintained by the USAge community. Supported by NSF Grant OPP-2235061.

## Acknowledgments

Design inspired by:
- [Hercules Dome Ice Core Project](https://herculesdome.org/)
- [IARPC Collaborations](https://www.iarpccollaborations.org/)

---

*Last updated: January 2026*
