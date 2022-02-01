# Minifier

A simple API that will return a pair of randomly generated UUID.

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

| **ENVIRONMENT VARIABLE** | **DESCRIPTION**              | **EXAMPLE**              |
| ------------------------ | ---------------------------- | ------------------------ |
| `DB_ACCESS_KEY`          | database connection password | password                 |
| `DB_SCHEMA`              | database name                | minifier                 |
| `DB_USER`                | database user                | root                     |
| `DB_HOST`                | database host                | mysql.example-server.com |

## API Reference

#### Minify a link

```http
  POST /api/minify
```

| Parameter | Type     | Description                     | Example                     |
| :-------- | :------- | :------------------------------ | --------------------------- |
| `url`     | `string` | **Required**. The URL to minify | https://the-ghost-boxes.com |

## Development

Build the project

```bash
$ git clone https://github.com/opeolluwa/minifier #clone the project
$ cd minifier #navigate to the project root directory
$ npm install #install project dependencies
$ sequelize db:create #create database tables
$ npm run dev # run the project in development mode
```

## Demo

Checkout a live [demo](https://minifier.mdbgo.io)

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Usage/Examples
