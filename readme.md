
# Swiggy Clone

A React application built as part of learning React.js, featuring a food delivery app interface inspired by Swiggy. Includes routing, search functionality, restaurant menus, and modern UI components.

## 🚀 Features

- **Responsive Design**: Built with Tailwind CSS for mobile-first responsive layouts
- **Routing**: Implemented using React Router DOM for seamless navigation between pages
- **Search Functionality**: Search through restaurants and food items
- **Restaurant Menu**: Detailed menu display for individual restaurants with ratings and pricing
- **Shimmer UI**: Loading states with skeleton screens for better UX
- **Error Handling**: Custom error pages for better user experience
- **Modern UI**: Clean and intuitive interface

## 🛠️ Tech Stack

- **React 19**: Latest version of React with modern hooks and features
- **React Router DOM**: For client-side routing
- **Parcel**: Fast, zero-configuration bundler
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript (ES6+)**: Modern JavaScript features

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/pankajkashp/Swiggy.git
   cd Swiggy
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

   The app will be available at `http://localhost:1234` (or another port if 1234 is busy).

## 📜 Available Scripts

- `npm start` - Starts the development server with hot reloading
- `npm run build` - Builds the app for production
- `npm test` - Runs tests (if configured)

## 📁 Project Structure

```
Swiggy/
├── src/
│   ├── components/
│   │   ├── Header.js          # Navigation header
│   │   ├── Body.js            # Main content area
│   │   ├── Search.js          # Search component
│   │   ├── RestaurantMenu.js  # Restaurant menu details
│   │   ├── Shimmer.js         # Loading skeleton
│   │   ├── Error.js           # Error boundary
│   │   └── ...
│   ├── utils/
│   │   ├── constants.js       # App constants
│   │   └── mocData.js         # Mock data
│   └── App.js                 # Main app component
├── index.html                 # HTML entry point
├── index.css                  # Global styles
├── package.json               # Dependencies and scripts
└── readme.md                  # This file
```

## 🎯 Components Overview

- **Header**: Navigation bar with logo and menu links
- **Body**: Displays list of restaurants with cards
- **Search**: Filters restaurants based on search input
- **RestaurantMenu**: Shows detailed menu for selected restaurant
- **Shimmer**: Skeleton loading components
- **Error**: Handles and displays error states

## 📚 Learning Outcomes

This project demonstrates:
- React component architecture and lifecycle
- State management with React hooks
- Routing with React Router DOM
- API integration concepts (mock data)
- Responsive design with Tailwind CSS
- Modern JavaScript practices (ES6+)
- Performance optimization techniques

## 🤝 Contributing

This is a learning project. Feel free to fork and experiment with the code. Pull requests are welcome!

## 📄 License

ISC License

---

**Note**: This is a clone/learning project inspired by Swiggy. All rights to the original design and branding belong to Swiggy.

    parcel - babel-  convert the code in js  we use in the format they understand

    in jsx for attriburtes it use the camel case like (tabIndex)
    React has two components 
         . class based components  (old method )
         . Funtional components   (new method)

    component compotion
      ek component ke ander ek or component


   two types of exports

     default export/import
      . export default component;
      . import component from "path"
    
    Named export/import
      . export const component;
      . import {compnent} from "path";


      video 6

      monolith:
        all the services or components like sms api ui authication in one area

      microservices
        all the components are in small apps and combine or connect acc to use for exp backend connect sms , api etc

      Fetch data direct is thorugh api
      api if two types

