<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/DSC-UIUC/research-bay">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Research Bay</h3>

  <p align="center">
    A web platform for efficiently connecting students to research opportunities and professors
    <br />
    <a href="https://github.com/DSC-UIUC/research-bay"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="">View Demo</a>
    ·
    <a href="https://github.com/DSC-UIUC/research-bay/issues">Report Bug</a>
    ·
    <a href="https://github.com/DSC-UIUC/research-bay/issues">Request Feature</a>
  </p>
</p>


## Table of Contents

* [About](#about)
  * [Background](#background)
  * [Solution](#solution)
  * [Structure](#structure)
  * [Technologies](#technologies)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


## About

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Research Bay is a community-driven project built by students at the Developer Student Club at University of Illinois at Urbana-Champaign (UIUC) that aims to provide a streamlined and standardized platform for UIUC professors and students to easily connect with research opportunities and talent.

### Background

TODO

### Solution

TODO

### Structure

Research Bay is built as a scalable web application that uses the principles of REST and Serverless to be efficient, modular, and open to future expansion. It is separated into two main components: a React.js frontend app and a Serverless backend API powered by multiple Firebase/GCP services, such as Cloud Functions, Storage, and Firestore. A mobile app in Flutter for Android is currently in the planning stage and would easily integrate with the existing backend.

For organized development, Research Bay's code is divided into the following three public Github repositories:

* [Frontend](https://github.com/DSC-UIUC/rbay-frontend)
* [Backend](https://github.com/DSC-UIUC/rbay-backend)
* [Data/ML](https://github.com/DSC-UIUC/rbay-data-ml)

More detailed documentation specific to each component can be found in each repository's README file.

### Technologies

* [Firebase](https://firebase.google.com/)
* [Google Cloud Platform](https://cloud.google.com/)
* [React.js](https://reactjs.org/)
  * [create-react-app](https://github.com/facebook/create-react-app)
  * [Material UI](https://material-ui.com/)
* [Node.js](https://nodejs.org/en/)
* [Algolia](https://www.algolia.com/)


## Getting Started (Public)

Due to the structural nature of Research Bay, only its React.js frontend is feasible to get locally up and running as its backend API is serverless and deployed to an internal Firebase project only accessible to developers in DSC @ UIUC. However, all code is publicly accessible.

To get Research Bay's frontend locally up and running, please follow the guide below.

### Prerequisites

The latest versions of the following software are required:
* [git](https://git-scm.com/downloads)
* [npm](https://www.npmjs.com/get-npm)

### Installation
 
1. Clone the repo
```sh
git clone https://github.com/DSC-UIUC/rbay-frontend.git rbay-frontend
cd rbay-frontend
```

2. Install NPM packages
```sh
npm install
```

3. Run
```sh
npm start
```

The React.js website should now launch at `localhost:3000`. Please post any issues with setup [here](https://github.com/DSC-UIUC/research-bay/issues).

<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo](https://github.com/github_username/repo)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=flat-square
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=flat-square
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=flat-square
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=flat-square
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=flat-square
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
