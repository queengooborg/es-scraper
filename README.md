# mdn-checker

Check MDN page structures

## Installation

```bash
npm i
npm run build
```

We don't have an npm publishing yet, although we may in the future.

## Usage

```bash
NODE_OPTIONS="--experimental-vm-modules" npm run mdn-checker ../content
```

where `../content` is the path to the MDN content repository.

To run the ES scraper:

```bash
npm run es:scrape
```

To sync the ES spec with upstream:

```bash
npm run es:sync
```
