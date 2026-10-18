# API-STORAGE

> This project was an assignment (task) from the Front-End Development diploma I studied at **Route Academy**. It's kept here only to document my learning, not as a production app.

A small mock REST API built with json-server. It serves `customers` and `transactions` data to practice working with a REST API from the front end.

## Endpoints

| Method | Endpoint | Description |
| --- | --- | --- |
| GET | `/customers` | List of customers |
| GET | `/transactions` | List of transactions |
| GET | `/transactions?customer_id=1` | Transactions for one customer |

## Run it locally

```bash
npm install
npm start
```

The API runs on http://localhost:3001 (or the `PORT` environment variable).

**Built with:** Node.js, json-server
