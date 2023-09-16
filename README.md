

# Low-Code Website Generation Platform 
This is a low-code website generation platform that allows users to easily create customized websites without extensive coding knowledge. The platform provides a web interface where users can input their desired website details, select options, and generate a fully functional website with customizable templates.
## Features

- **Form-Based Website Generation**: Users can fill out a form with various inputs such as site name, site type, template selection, font choices, color schemes, layout options, and database configuration.
- **Dynamic Template Rendering**: The platform dynamically renders the selected template based on the chosen site type and user inputs. It populates the template with the provided information to generate the HTML content of the website.
- **File Generation and Compression**: The platform generates the necessary files for the website, including the HTML file, CSS file, and database SQL file. It then compresses these files into a ZIP archive for easy download and deployment.
- **Multiple Site Types**: The platform supports different site types, including blogs, e-commerce sites, and portfolio sites. Each site type has its own pre-designed template and styling options.
- **Customizable Styling**: Users can select fonts, color schemes, navigation menu positions, and other styling options to customize the appearance of their websites.

- **Database Integration**: Users can provide database configuration details, and the platform generates a database SQL file for setting up the necessary database tables.

- **Error Handling**: The platform includes error handling mechanisms to catch and handle any errors that may occur during the website generation process. It provides informative error messages to assist users in troubleshooting.
## Installation and Usage
1. Clone the repository or download the project files.
2. Install the required dependencies using the package manager of your choice.
3. Run the server.js file using Node.js to start the web server.
4. Access the platform through your web browser and fill out the website generation form.
5. Submit the form to generate the website files and download the ZIP archive.
6. Extract the ZIP archive and deploy the generated files to a web server or local development environment.


## Dependencies

- Node + Express.js: Fast, unopinionated web framework for Node.js
- HTML, CSS and Javascript
- Archiver: Library for creating and manipulating ZIP archives
- Body-parser: Middleware for parsing HTTP request bodies
- EJS: Templating engine for generating HTML content
- MySQL: Database Generation based on users inputs



# How To Use
To clone and run this application, you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

```bash
git clone https://github.com/YourGithubUsername/low-code-generator
```

### Go into the repository
```bash
cd low-code-generator
```

### Install dependencies
```bash
npm install
```

### Run the app
```bash
npm start
```

## Autores

- [@offmtm](https://github.com/offmtm)

## Credits

This project is developed by Martim Moleiro @ Universidade Autonoma Lisboa.