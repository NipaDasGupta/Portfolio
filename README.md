# Portfolio

> A personal portfolio site built with the Academic theme for Hugo, showcasing projects, publications, and professional experience.

![Portfolio Preview](preview.png)

## Table of Contents

* [About](#about)
* [Features](#features)
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [Download](#download)
* [Contributing](#contributing)
* [License](#license)

## About

This repository contains a modern, responsive portfolio website powered by Hugo and the Academic theme. It is fully customizable and designed to highlight academic and professional achievements, projects, publications, and more.

## Features

* Clean, minimalist design optimized for academics and professionals
* Dark/light theme toggle
* Fully responsive across devices
* Support for publications, projects, talks, and blog posts
* Easy configuration via TOML/YAML files
* Built-in search and navigation

## Technologies

* [Hugo](https://gohugo.io/) - Static site generator
* [Academic Theme](https://sourcethemes.com/academic/) - Hugo theme for resumes and portfolios
* Go modules for dependency management
* Netlify for continuous deployment (optional)

## Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/NipaDasGupta/Portfolio.git
   cd Portfolio
   ```

2. **Install Hugo**

   Follow the [official guide](https://gohugo.io/getting-started/installing/) to install Hugo on your operating system.

3. **Run the development server**

   ```bash
   hugo server --themesDir config/_default --theme=academic --disableFastRender
   ```

   Navigate to `http://localhost:1313/` in your browser to preview your site.

## Usage

* **Configure your profile and content**

  * Edit `config/_default/config.toml` (or YAML) to set your name, links, and theme settings.
  * Add or modify content under the `content/` folder (e.g., `content/publication`, `content/project`).

* **Build for production**

  ```bash
  hugo --minify
  ```

  The generated files will be in the `public/` directory, ready to deploy to any static host.

## Download

You can download the latest version of this portfolio directly:

* **Download ZIP:**
  [Portfolio.zip](https://github.com/NipaDasGupta/Portfolio/archive/refs/heads/main.zip)

* **Clone via Git**:

  ```bash
  git clone https://github.com/NipaDasGupta/Portfolio.git
  ```

## Contributing

Contributions are welcome! Feel free to:

* Fork the repository
* Create a feature branch (`git checkout -b feature/YourFeature`)
* Commit your changes (`git commit -m "Add YourFeature"`)
* Push to the branch (`git push origin feature/YourFeature`)
* Open a Pull Request

Please adhere to the existing code style and include relevant documentation.

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
