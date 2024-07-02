# Currency Converter Wizard

Convert currencies effortlessly with Currency Converter Wizard, a web application that allows users to quickly check exchange rates between different currencies.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Overview](#overview)
- [API Uses](#api-uses)
- [Instructions for Use](#instructions-for-use)
- [Contribution](#contribution)
- [License](#license)

## Demo
[![Live Demo](https://img.shields.io/badge/Live%20Demo-Click%20Here-blue)](https://harshad313d.github.io/Currency-Converter-Wizard-/)


You can view a live demo of the Currency Converter Wizard at 



## Features

- **Currency Conversion:** Convert between various currencies with real-time exchange rates. From of 150+ country currencies
- **Customizable Options:** Select different base and target currencies.
- **Responsive Design:** Accessible and usable across different devices.
- **Swap Functionality:** Quickly switch between base and target currencies with a single click.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Fetch API for data retrieval
- [FreeCurrencyAPI](https://freecurrencyapi.com/) for currency exchange rates
- Flags API for displaying country flags

## Overview

Currency Converter Wizard simplifies currency conversion tasks by providing up-to-date exchange rates and a user-friendly interface. Users can specify the amount to convert, select base and target currencies, and view the calculated conversion instantly.

## API Uses

Currency Converter Wizard uses the FreeCurrencyAPI to fetch real-time exchange rates. The API key is securely managed and can be configured in the application settings.


## Instructions for Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/currency-converter-wizard.git
   ```
### Navigate to the Project Directory:

```bash
cd currency-converter-wizard
```
Install Dependencies
Install Node.js dependencies using npm:

```bash
npm install
```
Configuration
Create a .env file in the root directory of your project. Add your API key and any other environment variables:
```makefile
API_KEY="your api key "
```
Make sure to add .env to your .gitignore file to prevent it from being tracked by version control.

Run the Server
Start the Node.js server:

```bash
npm start
```
The server will start running on http://localhost:3000. You can access the application by navigating to this URL in your web browser.

Directory Structure
```bash
After cloning and installing dependencies, your project directory should look like this:
```
```java
currency-converter/
├── public/
│   ├── index.html
│   ├── styles.css
│   ├── app.js
├── .env
├── package.json
└── server.mjs
```
Dependencies

express: Fast, unopinionated, minimalist web framework for Node.js.
dotenv: Loads environment variables from a .env file into process.env.
node-fetch: A light-weight module that brings window.fetch to Node.js.
## Contribution
If you want to contribute to this project, feel free to fork it and submit your pull requests.
