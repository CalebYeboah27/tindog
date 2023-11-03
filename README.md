# Tindog Landing Page

Welcome to Tindog, where dogs meet their perfect playdate! 🐾

## Overview

Tindog is a whimsical landing page created to showcase the concept of a dating app for dogs. Whether your furry friend is looking for a partner for a game of fetch or a companion for a leisurely stroll, Tindog is the place to be. This landing page is built using Docker, making it easy to deploy and run in any environment.

## Features

- **Playful Design**: The landing page features a vibrant and playful design to capture the essence of a dog-friendly atmosphere.

- **Responsive**: Tindog is designed to be responsive, ensuring a seamless experience across various devices, from desktops to smartphones.

- **Dockerized**: With Docker, you can easily containerize and deploy Tindog in any environment without worrying about dependencies.

## Requirements

- [Docker](https://www.docker.com/) installed on your machine.

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/CalebYeboah27/tindog.git
    ```

2. Navigate to the project directory:

    ```bash
    cd tindog
    ```

3. Build the Docker image:

    ```bash
    docker build -t tindog .
    ```

4. Run the Docker container:

    ```bash
    docker run -p 5000:5000 tindog
    ```

5. Open your web browser and visit [http://localhost:5000](http://localhost:5000) to view the Tindog landing page.

## Customization

Feel free to customize the content and design of the landing page to suit your preferences. The main files you might want to modify are:

- `index.html`: Update the HTML content.
- `style.css`: Customize the styles.

## Contributing

If you'd like to contribute to Tindog, please fork the repository, create a new branch, make your changes, and submit a pull request.

