# README.md

# HackBot Web Application

This project is a web application that connects to the HackBot chatbot implemented in Python. The application provides a user-friendly interface for interacting with the chatbot, allowing users to submit queries and receive responses in real-time.

## Project Structure

```
hackbot-web
├── src
│   ├── static
│   │   ├── css
│   │   │   └── style.css
│   │   └── js
│   │       └── main.js
│   ├── templates
│   │   ├── base.html
│   │   └── index.html
│   ├── app.py
│   └── hackbot
│       ├── __init__.py 
│       └── hackbot.py
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd hackbot-web
   ```

2. **Install Dependencies**
   Make sure you have Python installed. Then, install the required packages using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   Start the web server by running:
   ```bash
   python src/app.py
   ```

4. **Access the Web Application**
   Open your web browser and navigate to `http://127.0.0.1:5000` to access the chatbot interface.

## Features

- User-friendly interface for interacting with the HackBot chatbot.
- Real-time responses from the chatbot.
- Clean and organized code structure for easy maintenance and updates.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.