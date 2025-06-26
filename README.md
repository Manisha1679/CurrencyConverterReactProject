# 💱 Currency Converter React Project

A simple and responsive currency converter application built with React. It allows users to convert between different currencies using real-time exchange rates

## 📌 Features

- 🔄 Real-time currency conversion
- 🌍 Supports multiple global currencies
- 🔃 Swap "From" and "To" currencies with a single click
- 🎯 Easy-to-use interface with input validation
- 📡 Fetches data using a custom React hook

## 🧰 Tech Stack

- ⚛️ React
- 🎣 Custom React Hooks
- 🌐 Public Currency API (via `useCurrencyInfo.js`)
- 💅 HTML, CSS, JavaScript


## 🚀 Getting Started

### ✅ Prerequisites

- Node.js (v14 or higher)
- npm or yarn

## 📦 Installation of the project

 1) Clone the repository<br>
   git clone https://github.com/Manisha1679/CurrencyConverterReactProject.git

 2) Navigate into the project directory<br>
   cd CurrencyConverterReactProject

 3) Install dependencies<br>
   npm install or yarn install<br>

 4) Run the app <br>
  npm start or yarn start<br>

5) Once the server is running, open your browser and visit:<br>
   http://localhost:3000


## How It Works 

 User enters the amount and selects the currencies.<br>
 The app fetches the latest exchange rate using a public API.<br>
 The result is instantly calculated and displayed.<br>
 Swap functionality allows reversing the currency pair.<br>

## API Reference
The project uses a public API to fetch exchange rates via the useCurrencyInfo.js hook. To change the data source:<br>
Open src/hooks/useCurrencyInfo.js<br>
Replace the fetch URL and response structure as per the new API.<br>

## Contributions are welcome!

Fork the repository<br>
Create a new branch: git checkout -b feature/YourFeature<br>
Commit your changes: git commit -m "Add feature"<br>
Push to the branch: git push origin feature/YourFeature<br>
Open a pull request<br>
