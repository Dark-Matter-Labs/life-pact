# LifePact Replication Website

This repository contains the code for the LifePact Replication website, originally built using Webflow and now deployed via GitHub Pages.

## Project Overview

The LifePact Replication website was designed to provide resources and information related to the LifePact initiative. It was built using Webflow for ease of design, but the code has been exported to this repository and is hosted using GitHub Pages for deployment.

**Live site**: [lifepactreplication.org](https://www.lifepactreplication.org/)

## Tech Stack

- **Webflow**: Used to design and develop the original site. The Webflow-generated code was exported for this repository.
- **HTML/CSS/JS**: The site uses standard HTML, CSS, and JavaScript. No frameworks or external libraries have been added.
- **GitHub Pages**: The static site is deployed and hosted via GitHub Pages.

## Deployment

The site is automatically deployed via GitHub Pages. To make updates:

1. Push any changes to the `main` branch.
2. GitHub Pages will automatically detect and deploy the latest version.

**GitHub Pages URL**: [https://dark-matter-labs.github.io/life-pact/](https://dark-matter-labs.github.io/life-pact/)

## Local Development

To make changes to the website locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/Dark-Matter-Labs/life-pact.git
    cd life-pact
    ```

2. Open the project folder in your favorite code editor.
3. Since this is a static website, you can open the `index.html` file directly in your browser for local development, or use a local server if you prefer.

    For example, using Python's built-in server:

    ```bash
    python -m http.server
    ```

    Then navigate to `http://localhost:8000` to view the site locally.

## How to Update Content

Since the site was exported from Webflow, all content is managed through static HTML files. To update content:

1. Edit the respective HTML files within the repository.
2. Push your changes to the `main` branch, and the site will be updated automatically via GitHub Pages.

### Common Changes

- **Text**: Open any of the `.html` files, find the section you want to edit, and update the text.
- **Images**: Images are stored in the `/images` directory. To replace an image, add your new image file to that folder and update the `src` attribute of the corresponding `<img>` tag in the HTML files.
- **CSS**: The site’s styles are located in the `/css` folder. Update the CSS files to change the look and feel of the site.
- **JavaScript**: Any custom scripts can be found in the `/js` folder.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure your changes are tested before submitting.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
