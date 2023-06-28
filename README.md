# React Router 6.4 Van Hosting App
This is a React application for a van hosting platform. It allows users to browse vans, view van details, and perform various actions related to hosting vans. The app utilizes client-side routing with React Router to provide a multi-page user interface.

## Features
- This app mostly focus on React Router
- Van detail pages with nested routes for managing van information, pricing, and photos
- Error handling for data loading
## Technologies Used
- React
- React Router
- ReactDOM
- JavaScript

## How React Router is Used in the App
- The React Van Hosting App utilizes React Router for its client-side routing needs. Here's how React Router is used within the app:

- Installation: The app includes the react-router-dom package as a dependency to work with React Router. It is installed using npm or yarn.

- Router Setup: The app sets up the router using the BrowserRouter component from react-router-dom. The BrowserRouter component wraps the entire app and provides the necessary routing functionality.

- Defining Routes: Routes are defined using the <Route> component from react-router-dom. Each <Route> component specifies a path and the corresponding component to render when that path matches the current URL.

- Nested Routes: The app utilizes nested routes to create a hierarchical structure for certain sections. Nested routes are defined by placing <Route> components inside other <Route> components, creating a parent-child relationship.

- Route Parameters: React Router supports route parameters, allowing dynamic segments within route paths. The app uses route parameters in the form of :id to handle dynamic van IDs in the route path.

- Linking and Navigation: The app uses the <Link> component from react-router-dom to create navigation links. The <Link> component renders an anchor tag that triggers the corresponding route when clicked, ensuring a smooth navigation experience.

- Route Rendering: React Router determines which route to render based on the current URL. When a route's path matches the URL, the corresponding component is rendered. The app utilizes the <Switch> component from react-router-dom to render only the first matching route.

- Route Hooks and Accessing Route Parameters: React Router provides hooks like useParams and useHistory to access route-related information within components. The app uses useParams to retrieve the van ID from the route parameters and fetches the corresponding van details.
