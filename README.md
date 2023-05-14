# webcrawler


# Web Crawler

This is a simple web crawler built using [Node.js](https://nodejs.org/) and [Puppeteer](https://pptr.dev/). The crawler can be used to scrape websites and collect data for various purposes.

## Requirements

- Node.js 12.x or higher
- npm or yarn package manager

## Installation

1. Clone the repository:

```bash
git clone https://github.com/username/web-crawler.git
```

2. Install dependencies:

```bash
cd web-crawler
npm install
```

## Usage

1. To start the crawler, run the following command:

```bash
npm start
```

2. The crawler will visit the specified website and scrape the data.

3. The scraped data will be saved to a JSON file in the `data/` directory.

## Configuration

The crawler can be configured by editing the `config.js` file. Here are the available options:

- `url`: The URL of the website to be scraped.
- `maxDepth`: The maximum depth to crawl. Default is `3`.
- `maxConcurrency`: The maximum number of concurrent requests. Default is `10`.
- `outputFile`: The path of the file to save the scraped data. Default is `data/output.json`.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.