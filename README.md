# Estate Flow

Estate Flow is a responsive real estate agency website. Visitors can browse featured homes, read about the agency, and reach the office from the header or footer.

The page is a single static site. There is no build step and no framework.

## Pages and sections

Everything lives on `index.html`:

- **Home** — hero with a call to make an enquiry
- **About** — agency overview and highlights
- **Service** — buy, rent, and sell focus areas
- **Property** — featured listings with price, location, and agent
- **Amenities** — building features such as parking, swimming, and security
- **Blog** — latest news cards
- **Contact** — office address, phone, and email in the header bar and footer

The header sticks to the top after you scroll. On smaller screens the navigation opens from a menu button.

## Contact shown on the site

| | |
| --- | --- |
| Email | [hello@estateflow.com](mailto:hello@estateflow.com) |
| Phone | [+1 (312) 847-2604](tel:+13128472604) |
| Office | 420 North Wabash Avenue, Suite 210, Chicago, Illinois |

The short address in the top bar is `420 N Wabash Ave, Chicago`.

## Tech

- HTML
- CSS (`assets/css/style.css`)
- JavaScript (`assets/js/script.js`) for the mobile menu and sticky header
- [Nunito Sans and Poppins](https://fonts.google.com/) from Google Fonts
- [Ionicons](https://ionic.io/ionicons) from a CDN

Colors, type, and spacing tokens are listed in `style-guide.md`.

## Run locally

Open `index.html` in a browser.

To serve it over HTTP from this folder:

```bash
python -m http.server 8080
```

Then visit `http://localhost:8080`.

## Project structure

```
EstateFlow/
├── index.html
├── favicon.svg
├── style-guide.md
├── assets/
│   ├── css/style.css
│   ├── js/script.js
│   └── images/
└── readme-images/
```
