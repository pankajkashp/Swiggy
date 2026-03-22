
# Namaste React

A React application built as part of learning React.js, featuring a food delivery app interface with routing, search functionality, and modern UI components.

## Features

- **Responsive Design**: Built with Tailwind CSS for mobile-first responsive layouts
- **Routing**: Implemented using React Router DOM for navigation between pages
- **Search Functionality**: Search through restaurants and food items
- **Restaurant Menu**: Detailed menu display for individual restaurants
- **Shimmer UI**: Loading states with skeleton screens
- **Error Handling**: Custom error pages for better user experience

## Tech Stack

- **React 19**: Latest version of React with modern hooks and features
- **React Router DOM**: For client-side routing
- **Parcel**: Fast, zero-configuration bundler
- **Tailwind CSS**: Utility-first CSS framework
- **JavaScript (ES6+)**: Modern JavaScript features

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd namreact
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

## Available Scripts

- `npm start` - Starts the development server with hot reloading
- `npm run build` - Builds the app for production
- `npm test` - Runs tests (if configured)

## Project Structure

```
namreact/
├── src/
│   ├── components/
│   │   ├── Header.js
│   │   ├── Body.js
│   │   ├── Search.js
│   │   ├── RestaurantMenu.js
│   │   └── ...
│   ├── utils/
│   │   ├── constants.js
│   │   └── mocData.js
│   └── App.js
├── index.html
├── index.css
├── package.json
└── readme.md
```

## Components

- **Header**: Navigation bar with logo and menu
- **Body**: Main content area displaying restaurants
- **Search**: Search functionality for restaurants
- **RestaurantMenu**: Detailed menu for selected restaurant
- **Shimmer**: Loading skeleton components
- **Error**: Error boundary component

## Learning Outcomes

This project demonstrates:
- React component architecture
- State management with hooks
- Routing with React Router
- API integration concepts
- Responsive design principles
- Modern JavaScript practices

## Contributing

This is a learning project. Feel free to fork and experiment with the code.

## License

ISC

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

