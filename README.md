# URL-Shortener

A simple and beginner-friendly URL Shortener built with Python and Flask.

This project allows users to convert long URLs into shortened links that redirect to the original address. It's designed as an educational project for those who want to learn about web development, Flask, and basic persistent data handling.

## Features

- Shorten any URL to a compact, easy-to-share link.
- Persistent storage of shortened URLs using a JSON file.
- User-friendly web interface.
- Simple and clean codebase, ideal for beginners.

## Demo

![Screenshot](screenshot.png) <!-- Add a screenshot if available -->

## Getting Started

### Prerequisites

- Python 3.x
- pip (Python package manager)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/theonlykingpin/URL-Shortener.git
   cd URL-Shortener
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. **Start the application:**

   ```bash
   python main.py
   ```

2. **Open your browser and go to:**

   ```
   http://127.0.0.1:5000/
   ```

3. **Shorten a URL:**

   - Enter your long URL in the input box and click "Shorten URL".
   - You will receive a shortened URL, which you can share or use to be redirected to the original website.

### Project Structure

```
URL-Shortener/
├── main.py             # Main Flask application
├── requirements.txt    # Python dependencies
├── urls.json           # Persistent storage for shortened URLs
├── templates/
│   └── index.html      # HTML template for the web UI
└── README.md           # Project documentation
```

## How It Works

- When a URL is submitted, the app generates a random short string.
- The mapping between the short URL and the original URL is saved in a `urls.json` file.
- Accessing the short URL will redirect you to the original long URL.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your proposed changes.

Please make sure to update and add tests as necessary.

## License

This project is licensed under the [MIT License](LICENSE).

---

Made with ❤️ by [Reza Rohani](https://github.com/theonlykingpin)
