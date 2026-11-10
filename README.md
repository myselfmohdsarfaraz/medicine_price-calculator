# Medicine Price Calculator

A small web app I built to work out the price of part of a medicine strip, apply a discount, and add up a whole bill.

## What it does

- Enter the strip price and how many parts the strip has (for example, 10 tablets).
- Tap how many parts were sold.
- Choose a discount with the quick buttons (0, 5, 10, 15, 20, 25%) or type any percentage.
- Tap **Add to bill** for each medicine. The bill shows every item and the total.
- Remove one item, or clear the whole bill.

## How the price is calculated

```
price of parts = strip price x parts sold / parts in strip
discount       = price of parts x discount % / 100
customer pays  = price of parts - discount
```

The bill total is the sum of every item's final price.

## Built with

HTML, CSS and JavaScript. No libraries or build step, the whole app is one `index.html` file.

## Run it

Download or clone the repository and open `index.html` in any browser.

## Live version (GitHub Pages)

Turn on Pages under **Settings > Pages**, choose the `main` branch and `/ (root)`, and the app is served at
`https://myselfmohdsarfaraz.github.io/medicine-calculator/`.

## Ideas for later

- Medicine names in the bill
- Print or share the bill
- Save the bill so it survives a page refresh

## Author

Mohd Sarfaraz - [@myselfmohdsarfaraz](https://github.com/myselfmohdsarfaraz)
