# Order Enricher Microservice

## Overview

This is a Spring Boot microservice that processes and enriches order data by combining raw order events with customer and product information. The enriched order data is persisted to PostgreSQL and exposed via RESTful APIs.

## Features

- POST endpoint to receive raw orders (`/orders`)
- Enriches orders with customer and product data
- Persists enriched orders in PostgreSQL
- GET endpoint to retrieve enriched order (`/orders/{orderId}`)
- Optional: Redis caching support (configurable)
- JSON-based ingestion for customer and product information
- Uses Gson for parsing dynamic customer/product data

## Tech Stack

- Java 17+
- Spring Boot
- Spring Data JPA
- REST APIs
- PostgreSQL
- Docker 
- Gson
- Lombok
- Redis 



