<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#run-application">Run the application</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot][product-screenshot]

***This is a side project to emulate E-commerce webpage, where you can browse, add, modify, search and purchase any kinds of products!***

This project consists of 
* React application
* [Springboot application](https://github.com/kyddaniel/SpringBoot_E-Commerce) as backend to handle the data and comuunications between database
* Postgres SQL database


### Built With

This frontend side is built with

* [![React][React.js]][React-url]



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

NPM is required for running the project, please install npm if you haven't installed it yet
  ```sh
  npm install npm@latest -g
  ```

### Installation

To start the frontend side of the application, please follow the below steps

1. Clone the repo
   ```sh
   https://github.com/kyddaniel/springboot-e-commerce-frontend.git
   ```
2. Install the project NPM packages
   ```sh
   npm install
   ```
3. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```

### Run application
<a id="run-application"></a>

To run the application

1. Start the [backend side](https://github.com/kyddaniel/SpringBoot_E-Commerce) of the application
2. Start the frontend side application with
   ```sh
   npm run dev
   ```
3. Done! You can now browse the application in
   ```sh
   http://localhost:5173/
   ```



<!-- USAGE EXAMPLES -->
## Usage



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot]: src/assets/screenshot.png
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/