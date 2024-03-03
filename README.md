# MAD-Project (News-Aggregator)

This project is a news aggregator that fetches news data from various news websites, stores it in a MongoDB database using a Python web scraper, and provides it through API endpoints using a Node.js backend. The news data can be accessed and displayed in a Flutter application.

## Detail Readme

### Web-Scaper: [Web-Scaper.md](https://github.com/H-R-S/MAD-Project/blob/main/Web-Scraper/web-scraper.md)
### Backend: [Backend.md](https://github.com/H-R-S/MAD-Project/blob/main/Backend/backend.md)
### Application: [Application.md](https://github.com/H-R-S/MAD-Project/blob/main/Application/application.md)

## Getting Started

## Web Scraper (Python)

## Prerequisites

- Python
- MongoDB

## Installation

1. #### Clone the repository:
```
git clone https://github.com/H-R-S/MAD-Project
```

2. #### Project:
```
cd Web-Scraper
```

3. #### Install the required packages
```
pip install pymongo
```
```
pip install scrapy
```

4. #### Install the requirements.txt
```
pip install -r requirements.txt
```

5. #### Run the web scraper:
```
scrapy crawl news-crawler
```

## Backend (Node.js)

## Prerequisites

- Node.js
- MongoDB

## Installation

1. #### Clone the repository:
```
git clone https://github.com/H-R-S/MAD-Project
```

2. #### Navigate to the project directory:
```
cd Backend
```

3. #### Installing Node Modules
```
npm install
```

4. #### Installing Express
```
npm install express
```

5. #### Installing MongoDB
```
npm install mongodb
```

6. #### Starting the Server
```
npm api.js
```

#### The server should now be running at http://localhost:3000.

### Using the API

You can access news data through the following API endpoints:

#### Express News EndPoint:
```
/express-news: Get news from Express News.
```

#### Geo News EndPoint:
```
/geo-news: Get news from Geo News.
```

#### Bol News EndPoint:
```
/bol-news: Get news from Bol News.
```

Example usage:
```
http://localhost:3000/geo-news
```

# Application (Flutter)

This Flutter application is a news aggregator that fetches news data from a backend server and displays it to the user.

## Getting Started

Follow these steps to get the project up and running on your local machine or emulator.

### Prerequisites

Before you begin, make sure you have Flutter installed on your machine. You can follow the official Flutter installation guide [here](https://flutter.dev/docs/get-started/install).

1. ### Cloning the Repository
```
git clone https://github.com/H-R-S/MAD-Project
```

2. #### Project:
```
cd Application
```

3. #### Installing Dependencies
```
flutter pub get
```

6. #### Running the App
```
flutter run
```

Once the app is running, you should see the news articles displayed on the screen.
