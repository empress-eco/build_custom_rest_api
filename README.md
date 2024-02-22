<p align="center">
  <a href="https://empress.eco/">
    <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Elevate Your API Creation with Empress</h3>
  <p align="center">
    A powerful, user-friendly tool for streamlined and efficient custom API creation.
    <br />
    <a href="https://grow.empress.eco/"><strong>Explore the Documentation »</strong></a>
    <br />
    <br />
    <a href="https://grow.empress.eco/">Support</a>
    ·
    <a href="https://github.com/empress-eco/build_custom_rest_api/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/build_custom_rest_api/issues">Request Feature</a>
  </p>
</p>

## About The Project
The Empress Custom REST API Builder is designed for developers who aim to build and manage custom APIs with ease and efficiency. This tool saves time, ensures uniformity across applications, and enhances your API creation process.

### Key Features
- Hassle-free API creation
- Consistent JSON responses for uniformity
- Middleware support for additional functionality
- Robust error handling for smooth operation

This project is built with [Empress](https://Empress.io/), a major framework renowned for its simplicity and efficiency.

## Technical Stack and Setup Instructions
### Prerequisites
Ensure Empress is installed on your system.

### Installation
To set up your development environment, follow these steps:

1. Clone the repository from the command line:
```sh
$ git clone https://github.com/empress-eco/build_custom_rest_api.git
```
2. Navigate into the project folder:
```sh
$ cd build_custom_rest_api
```
3. Install the project using bench:
```sh
$ bench get-app .
```

## Usage
With Empress Custom REST API Builder, you can easily create and manage your APIs. Here's a quick start guide:

1. Declare a function that accepts `*args` and `**kwargs` parameters and decorate it with the api function decorator.
2. Use our `response.JSONResponse` class to handle JSON responses uniformly.
3. Use JSON Schema to describe your data format and jsonschema to validate it.
4. Use the `request.api` decorator to validate your data against a defined schema.
5. Implement middlewares to validate user tokens, session ids, or any additional functionality.

You can find detailed information and code examples in our [documentation](https://grow.empress.eco/).

## Contribution Guidelines
We welcome and appreciate contributions! Here's how you can contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License and Acknowledgements
This project is licensed under the MIT License. Your contributions are also licensed under the MIT License.

We extend our heartfelt gratitude to the Empress Community for their foundational contributions to this project. Their innovation and dedication have been instrumental in shaping the functionalities we rely on, and we are profoundly grateful for their support.