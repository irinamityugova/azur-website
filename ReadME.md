# Azur Agency Website

Non-profit creative services website for [Azur Agency](https://azur-agency.org), built and maintained by volunteers at DarkMode Devs.

## Links

- **Live site:** https://azur-agency.org/
- **Public repo:** https://github.com/devftrejo/AzurAgencyWebsite

## Built with

- HTML, CSS, JavaScript
- [Bootstrap 5](https://getbootstrap.com/)
- [npm](https://www.npmjs.com/) + [lite-server](https://github.com/johnpapa/lite-server) (dev server)
- [Firebase Hosting](https://firebase.google.com/docs/hosting)
- Third-party libraries: AOS, Swiper, GLightbox, Isotope, Boxicons, Bootstrap Icons, animate.css

## Development

### Prerequisites

- Node.js / npm
- Firebase CLI (`npm install -g firebase-tools`) for deployment

### Setup

```bash
npm install
npm start        # live-reload dev server at http://localhost:3000
```

### Deployment

```bash
firebase deploy                   # deploy all Firebase services
firebase deploy --only hosting    # deploy website only
```

## Architecture

Static multi-page site — no framework, no build step. All pages are independent HTML files in `public/`. Shared elements (topbar, header, footer, vendor scripts) are manually duplicated in every page; there is no templating system.

## Authors

- [Fernando Trejo](https://www.linkedin.com/in/devftrejo/)
- [Irina Mityugova](https://www.linkedin.com/in/irina-mityugova/)
- [Azur Agency](https://www.linkedin.com/company/creativeazur/)

## License

No license — all rights reserved. See https://choosealicense.com/no-permission/ for what this means.
