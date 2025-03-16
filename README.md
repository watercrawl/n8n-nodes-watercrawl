# WaterCrawl Nodes for n8n

This is a community node for [n8n](https://n8n.io/) that provides integration with [WaterCrawl](https://watercrawl.dev) - a powerful web scraping and crawling API.

## Installation

To install this community node, please follow the official [n8n community node installation guide](https://docs.n8n.io/integrations/community-nodes/installation/).

## Features

### Crawl Operations
- **Scrape URL**: Extract data from any webpage with a single request, supports various options:
  - Wait time after page load
  - Custom timeout settings
  - HTML content inclusion
  - Link extraction
  - Main content filtering
  - Cookie acceptance handling
  - Custom locale settings

- **Create Crawl Requests**: Start larger crawling jobs with advanced options:
  - Spider configuration (depth, domain limits, etc.)
  - Page rendering settings
  - Custom plugins and extensions

- **Get Crawl Request Details**: Retrieve information about a specific crawl job
  - Status updates
  - Creation timestamps
  - Configuration details

- **List Crawl Requests**: View all your crawling jobs with pagination support

- **Get Crawl Results**: Retrieve the data extracted from crawling operations
  - Download full results
  - Filter by various criteria

- **Stop Crawl**: Cancel running crawl jobs to save resources

### Advanced Features
- **Asynchronous Processing**: Start jobs and retrieve results later
- **Synchronous Mode**: Wait for results in a single request
- **Detailed Metadata**: Access comprehensive information about crawled pages
- **Customizable Extraction**: Configure exactly what data to retrieve

## Development

For setting up local development and testing your n8n community node, please refer to these resources:

1. Clone the repository
2. Install dependencies:
   ```bash
   pnpm install
   ```
3. Build the code:
   ```bash
   pnpm build
   ```

### Testing

For testing your node, follow the [official n8n testing guide](https://docs.n8n.io/integrations/creating-nodes/test/).

Run tests with:

```bash
pnpm test
```

### Commit Guidelines

This project uses [Conventional Commits](https://www.conventionalcommits.org/) for semantic versioning. When committing changes, use:

```bash
pnpm commit
```

This will guide you through creating a properly formatted commit message.

## License

[MIT](LICENSE.md)
