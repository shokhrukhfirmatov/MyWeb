[README.md](https://github.com/user-attachments/files/33484061/README.md)
# MyWeb
# StayHaven — Hotel Booking Frontend

A responsive hotel discovery and booking-request demo built with plain HTML, CSS, and JavaScript. It is designed to publish directly with GitHub Pages.

## What's included

- Responsive landing page and mobile navigation
- Six sample stays with photos, locations, nightly prices, and ratings
- Destination search, category filters, and sorting
- Favourite/save buttons
- Booking dialog with date validation, guest selection, and estimated total
- Demo confirmation screen and newsletter form
- No build tools, package installation, or server required

## Run it locally

1. Download or extract this folder.
2. Open `index.html` in a browser.
3. Internet is required for the remote Unsplash photos and Google Fonts.

You can also use Visual Studio Code with the Live Server extension, but it is optional.

## Publish on GitHub Pages

1. Sign in to GitHub and create a **new public repository** (for example, `stayhaven-hotel-booking`).
2. On the repository page, select **Add file → Upload files**.
3. Upload `index.html`, `styles.css`, `script.js`, and `README.md` from this folder. Upload the files themselves to the repository root, not the ZIP file.
4. Commit the changes.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then save.
8. Wait a minute or two. GitHub will show the published site URL in the Pages section.

## Important limitations

This is a **frontend demo only**. The booking form calculates an estimated total and displays a demo confirmation; it does not check live availability, take payment, send email, or create a real hotel reservation. The newsletter form does not store email addresses.

For real bookings, connect a secure backend or booking provider. Never put private API keys, payment secrets, or database credentials in frontend JavaScript.

## Customise it

- Edit hotel names, locations, prices, ratings, and categories in `index.html` and the `hotels` array in `script.js`.
- Change visual styling in `styles.css`.
- Replace the remote image URLs in `styles.css` with your own photos if desired.
- Update the contact email in `index.html`.
