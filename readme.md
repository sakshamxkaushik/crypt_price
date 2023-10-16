# Crypto Prices Web App


![Crypto Prices Web App Screenshot](https://github.com/sakshamxkaushik/crypt_price/blob/main/Screenshot.jpg)

The Crypto Prices Web App is a simple web application that provides real-time cryptocurrency price information. It fetches data from the CoinGecko API and displays it in an easy-to-read format. This readme provides instructions on how to run the application and offers a brief overview of its features.

## Features

- Real-time cryptocurrency price updates.
- Dark mode support for improved visibility.
- Displays the last update time to keep users informed.

## Prerequisites

Before running the Crypto Prices Web App, ensure you have the following installed on your system:

- [Go](https://golang.org/dl/)
- [Tailwind CSS](https://tailwindcss.com/docs/installation)

## Installation and Usage

1. **Clone the Repository** or create a project folder and place the `main.go` and `template.html` files in it.

2. **Generate the CSS File** using Tailwind CSS:

    ```bash
    tailwindcss -o index.css -m --content template.html
    ```

3. **Start the Go Web Server:**

    ```bash
    go run main.go
    ```

4. **Access the Web App:**

    Open your web browser and go to [http://localhost:8080](http://localhost:8080) to use the Crypto Prices Web App.

## Credits

- This project uses data from the [CoinGecko API](https://coingecko.com/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The project structure and codebase were inspired by various web development and Go resources.

Please feel free to customize this readme with additional information about your project, such as any future updates, deployment instructions, or additional features.
