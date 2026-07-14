# Ricardo Flores Portfolio

Personal portfolio site for Ricardo Flores, Product Engineer.

## Stack

- HTML
- CSS
- Browser-native JavaScript when needed
- GitHub Pages

## Project structure

```text
.
├── assets/
│   ├── badges/
│   ├── css/
│   └── images/
├── index.html
└── README.md
```

## Run locally

From the project directory, start a local server:

```sh
python3 -m http.server 4174
```

Open [http://127.0.0.1:4174](http://127.0.0.1:4174) in a browser.

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**.
4. Select the branch and the repository root (`/`).
5. Save and use the published URL shown by GitHub.

GitHub Pages serves this site as static files. Client-side interactions and animations work normally; features requiring private credentials or server-side processing should use a separate backend service.
