# Qtrip Static Website

This is a simple static website project built using Qtrip.

## Overview

Qtrip is a lightweight static website generator that simplifies the process of creating and deploying static websites. This project serves as a basic template for building your static website using Qtrip.

## Features

- **Simplicity:** Qtip focuses on simplicity and ease of use, allowing you to create static websites quickly.
- **Markdown Support:** Write your content in Markdown for easy formatting.
- **Customization:** Customize the look and feel of your website using CSS and HTML templates.
- **Deployment:** Easily deploy your static website to hosting providers like GitHub Pages, Netlify, or any web server.

## Getting Started

1. **Clone the Repository:** Clone this repository to your local machine.

   ```bash
   git clone https://github.com/BoddepallyVenkatesh06/qtip-static-website.git
   cd qtrip-static-website
   ```

2. **Install Qtip:** If you haven't already, install Qtip globally on your machine.

   ```bash
   npm install -g qtrip
   ```

3. **Initialize Your Website:** Run the following command to initialize your website and create the necessary folder structure.

   ```bash
   qtrip init
   ```

4. **Edit Content:** Replace the content in the `src` directory with your Markdown files. You can also customize the HTML and CSS in the `template` directory to match your design.

5. **Generate the Website:** Run the following command to generate your static website.

   ```bash
   qtrip build
   ```

6. **Preview Locally:** You can preview your website locally by running a local server. For example, you can use Python's built-in HTTP server:

   ```bash
   python -m http.server
   ```

   Your website should now be accessible at http://localhost:8000.

7. **Deployment:** To deploy your website, follow the deployment instructions for your chosen hosting provider.

## Directory Structure

- `src/`: Contains your Markdown content and other assets.
- `template/`: Contains the HTML templates and CSS for your website.
- `dist/`: The generated static website files will be placed here.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Qtrip is a fantastic tool for creating static websites.
- Thanks to the open-source community for their contributions.

## Contact

If you have any questions or need assistance, feel free to reach out to [Venky Kumar](mailto:venkykumar06@email.com).

Happy coding!
