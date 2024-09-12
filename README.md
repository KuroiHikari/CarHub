# CarHub website using Next.js and API from RapidAPI

This is a web application built with Next.js that allows users to search and explore various car models, view detailed specifications, and generate images of cars from different angles. It uses data from multiple APIs hosted on RapidAPI for car specifications and car image generation.

![image](https://github.com/user-attachments/assets/c05e5257-f7e8-4133-b77f-f31a2d401552)

## Features
- **Car Search:** Search for any car model using a user-friendly search interface
- **Car Specifications:** View detailed information such as kW, weight, price, fuel type, etc., for each car model
- **Car Images:** Generate images of cars from different angles to visualize the car better
- **Responsive Design:** The site is responsive and works seamlessly across various devices

## Technologies Used
- **Frontend:** Next.js
- **APIs:** Car specifications and Car image API from RapidAPI

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

### Prerequisites

Ensure that you have the following installed on your machine:
- **Node.js**
- **Git**: To clone the repository

### Installation
#### 1. Clone the repository:
```bash
git clone https://github.com/KuroiHikari/CarHub.git
```

#### 2. Set up the FrontEnd:
- Make sure you're in CashFlare/frontend folder
```bash
npm install
```

#### 3. API keys:
- You will need to create an account on [RapidAPI] and get API keys from [Car API](https://rapidapi.com/carapi/api/car-api2) and [Cars by API-Ninjas](https://rapidapi.com/apininjas/api/cars-by-api-ninjas)
- Replace your API keys in CarHub/utils/index.ts (YOUR_CAR_API_KEY) and (YOUR_NINJA_CAR_API_KEY)

### Running the Application
- Make sure you're in CarHub folder
``` bash
  npm run dev
```

### URLs
- FrontEnd => http://localhost:5014/
