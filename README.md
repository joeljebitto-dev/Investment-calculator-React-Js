# Investment Calculator - React JS

A simple investment calculator built with React, Vite, and Tailwind CSS. The app lets users enter investment details and view a year-by-year projection of investment growth, interest earned, total interest, and invested capital.

## Features

* Interactive investment input form
* Initial investment input
* Annual investment input
* Expected return input
* Investment duration input
* Year-by-year results table
* Projected investment value calculation
* Annual interest calculation
* Total interest display
* Invested capital display
* Currency formatting using the browser `Intl.NumberFormat` API
* Clean React component structure
* Tailwind CSS styling

## Tech Stack

* React
* Vite
* Tailwind CSS
* JavaScript
* ESLint

## Project Structure

```text
Investment-calculator-React-Js/
├── src/
│   ├── components/
│   │   └── InputField.jsx
│   ├── sections/
│   │   ├── Header.jsx
│   │   ├── InputSection.jsx
│   │   └── OutputSection.jsx
│   ├── util/
│   │   └── investment.js
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── package.json
└── README.md
```

## How It Works

The calculator takes four values:

* Initial investment
* Annual investment
* Expected annual return
* Duration in years

For each year, it calculates:

* Interest earned during that year
* Investment value at the end of the year
* Annual investment added
* Total projected values shown in a table

The main calculation logic is handled in:

```text
src/util/investment.js
```

## Installation

Clone the repository:

```bash
git clone https://github.com/joeljebitto-dev/Investment-calculator-React-Js.git
cd Investment-calculator-React-Js
```

Install dependencies:

```bash
npm install
```

Or, if you use pnpm:

```bash
pnpm install
```

## Running the App

Start the development server:

```bash
npm run dev
```

Or with pnpm:

```bash
pnpm dev
```

Then open the local URL shown in the terminal, usually:

```text
http://localhost:5173
```

## Available Scripts

```bash
npm run dev
npm run build
npm run lint
npm run preview
```

Or with pnpm:

```bash
pnpm dev
pnpm build
pnpm lint
pnpm preview
```

## Build for Production

```bash
npm run build
```

The production-ready files will be generated in the `dist/` directory.

## Notes

* This is a frontend-only calculator.
* Results are estimates and should not be treated as financial advice.
* The current formatter displays values in USD.
* The calculation assumes a fixed annual return rate and fixed annual contribution.

## Future Improvements

* Add validation for negative or empty values
* Add support for different currencies
* Add charts for visualizing investment growth
* Add monthly contribution mode
* Add inflation-adjusted returns
* Add compound frequency options
* Improve mobile responsiveness
* Add unit tests for investment calculations
* Fix display labels and spelling, such as `Expected Return` and `Invested Capital`

## Author

Built by [Joel Jebitto](https://github.com/joeljebitto-dev).
