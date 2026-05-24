# Hammersmith Christian Fellowship — Website

Premium church website for HCF, Dalling Road, Hammersmith, London W6 0HE.

## Deployment (GitHub Pages)

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch: `main`, folder: `/ (root)`**
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Structure

```
/
└── index.html      ← Complete single-file website (all CSS & JS inline)
└── README.md
```

## Notes on Images

Staff photos (Keith Berry, Henry Ford, Juvina Vilela) and the church building
photos are currently served from the Wix CDN. If hotlinking is blocked after
migrating away from Wix, download the images and place them in an `/images/`
folder, then update the `src` paths in `index.html` accordingly.

## Contact

- Email: churchhcf@gmail.com
- Phone: 07399 092232
- Address: Dalling Road (on Furber Street), Hammersmith, London W6 0HE
