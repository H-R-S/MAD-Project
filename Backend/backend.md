# News Aggregator Project

This project is a news aggregator that fetches news data from a MongoDB database and provides it through API endpoints.

## Prerequisites

- Node.js
- MongoDB

## Installation

1. #### Clone the repository:
Clone the repository to your local machine using the following command:
```
git clone https://github.com/your-username/news-aggregator.git
```

2. #### Project:
Navigate to the project directory:
```
cd Backend
```

3. #### Installing Node Modules
Install the required Node.js modules for the project:
```
npm install
```

4. #### Installing Express
Install Express, a Node.js web application framework:
```
npm install express
```

5. #### Installing MongoDB
Install the MongoDB package for Node.js:
```
npm install mongodb
```

6. #### Starting the Server
Start the server:
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