# Vue2 + Vue-Router2 Starter Demo

This project is built using Vue2 and Vue-Router2, and is based on a modified version of the official Vue CLI. It includes custom examples and comments to help new learners better understand the framework.

**This is especially helpful for beginners who find the official Vue CLI a bit overwhelming.**

## Features

1. **Complete Vue-Router2 navigation examples**  
   The project includes detailed examples of how to use Vue-Router2 for navigation and route management.

2. **Customizable route titles**  
   Each route supports a custom title, including special support for displaying the title in WeChat and enabling WeChat sharing with custom titles.

3. **Pre-split components**  
   Components have been split out and organized. You can easily add, remove, or modify components based on your own examples.

4. **Modular design**  
   The project is modular, and custom JavaScript files can be easily imported and used.

5. **Automatic HTTP server on production build**  
   After building the production files, an HTTP server will automatically start, and the browser will open to preview the production environment (unlike the official Vue CLI which only handles resource bundling).

## Installation

To install the project dependencies, run:

```bash
npm install
```

## Running the Development Environment

To start the development server, run:

```bash
npm run dev
```

This will launch the application in the development environment, with hot-reloading enabled for easier debugging and development.

## Running the Production Environment

To build the application for production and launch an HTTP server, run:

```bash
npm run build
```

This will create a production build of the application, start a local HTTP server, and open your browser to preview the production environment.

## Testing

### Unit Testing

To run the unit tests, use the following command:

```bash
npm run unit
```

### End-to-End Testing

For end-to-end testing, run:

```bash
npm run e2e
```

### Run All Tests

To run both unit and e2e tests, use:

```bash
npm test
```

## Project Structure

The project is organized as follows:

- `src/`: Contains the source code for the project, including components, views, router, and custom JavaScript files.
- `src/components/`: Houses individual Vue components.
- `src/router/`: Contains the Vue-Router2 setup and route definitions.
- `src/assets/`: Contains static assets such as images, stylesheets, etc.
- `public/`: Holds the public-facing files, like `index.html`, which will be served in production.
- `build/`: Contains configuration files for webpack and other build tools.
- `test/`: Houses unit and e2e test files.

## Customizing the Router

The project includes a working Vue-Router2 setup with customizable route titles. You can easily modify the route titles by updating the `meta.title` field in each route definition.

Example route definition with custom title:

```js
{
  path: '/example',
  component: ExampleComponent,
  meta: {
    title: 'Custom Page Title'
  }
}
```

The title will automatically update based on the current route and will display correctly in WeChat, including when shared.

## Continuous Updates

We are continuously improving and updating this project with more examples and features. If you like the project, feel free to star the repository! Thank you for your support!

---

Enjoy coding with Vue2 + Vue-Router2! 🚀

