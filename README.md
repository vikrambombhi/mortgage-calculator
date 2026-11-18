# Mortgage Calculator

A simple, mobile-friendly mortgage calculator in a single static `index.html` file. It has no dependencies and no build step.

- Inputs: home price, down payment ($ or %), interest rate, fixed/variable, amortization, and optional annual property tax and monthly maintenance fees
- Shows the total monthly payment, broken down into mortgage, tax, and fees
- Variable-rate mode shows what the payment would be if rates moved ±1%
- Compounding: semi-annual for fixed and monthly for variable (the Canadian convention), or set one manually
- Everything is saved in `localStorage` on your device

## Hosting on GitHub Pages

1. Push to `main`.
2. In the repo, go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, then pick `main` and `/ (root)`.
3. The site will be live at `https://vikrambombhi.github.io/mortgage-calculator/`.

## Local use

Open `index.html` in a browser.
