# Nation Station

![Nation Station Logo](src/assets/logo/nation_station.png)

Nation Station is a country guide app built with Vue.js and Bootstrap. It allows users to explore and learn more about different countries, providing information about their cultures, landmarks, and more.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Features

- Home page with a visually appealing hero section to prompt users to explore countries.
- Country selection feature to choose a specific country and view detailed information.
- Integration with Unsplash API to dynamically generate images based on the selected country.

## Usage

- 0n the home page, users can explore countries by selecting a country from the provided options or by using the search functionality.
- After selecting a country, users are presented with detailed information about that country, including cultural highlights, landmarks, and travel tips.
- Users can navigate back to the home page or explore other countries through the navigation menu.

## Dependencies

The main dependencies used in this project are:

- Vue.js: A progressive JavaScript framework for building user interfaces.
- Bootstrap: A popular CSS framework for building responsive and mobile-first websites.
- Unsplash API: An API for accessing a vast collection of high-quality images.

For a complete list of dependencies, refer to the `package.json` file.

## Contributing

Contributions are welcome! If you would like to contribute to Atlas Insight, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Implement your changes and write tests if applicable.
4. Commit and push your changes to your forked repository.
5. Submit a pull request, explaining the changes you made.

## License

This project is licensed under the [MIT License](LICENSE).

### Design

- Primary: $yellow-500

- Secondary: $blue-800

- Alt: $gray-600

### Commit Log

---

7/12/23

- Project Reset - CDN integration: Clearing previous content and integrating Vue.js and Bootstrap via CDN

  1. Cleared previous files and commit history
  2. Switched from local installation to using Vue.js via CDN
  3. Updated project files and configurations accordingly
  4. Verified functionality and confirmed successful integration
  5. Refactor project structure, add logo to README.md, and update dependencies

   This commit marks a project reset, removing previous content and transitioning to using Vue.js via CDN. The project has been reconfigured to utilize the Vue.js library directly from the CDN, ensuring efficient loading and availability.

7/11/23

- CREATE: vue-app nation_station & installed vue-router

  1. Designed the Nation Station logo, adding a visually appealing brand identity to the application.
  2. Added initial hero images to enhance the visual appeal of the home page.
  3. Created the routes.js, HomePage.vue, and header-comp.vue files. These components lay the foundation for the application's routing, home page layout, and header component.
  4. Configured the main.js file to set up the Vue Router instance and connect it to the application.
  5. Installed vue-router, a vital dependency for handling routing in the Vue application, ensuring seamless navigation and component rendering.

- feat: Set up initial project structure and configuration
  1. - Initialize Vue.js project with Vue CLI
  2. Install and configure Bootstrap for styling
  3. Create basic folder structure (src/assets, src/components, src/views)
  4. Add Home.vue component with a hero section
  5. Update App.vue with header, main, and footer sections
  6. Add .gitignore file to exclude node_modules and build artifacts

This commit sets up the initial project structure, adds Bootstrap for styling, and creates the Home component as the app's landing page. The App component is also updated to include header, main, and footer sections, and a .gitignore file is added to exclude unnecessary files from version control.
