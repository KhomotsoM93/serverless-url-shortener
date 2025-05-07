# Serverless-URL-Shortener

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)

## Project Overview
---

A simple serverless application built using AWS services to shorten long URLs. This project demonstrates how to build a fully functional URL shortener using:

- AWS Lambda : Generate short code and save and fetch original URLs (in memory)
- Amazon API Gateway : Provide HTTPS endpoints to interact with Lambda
- IAM : Manage access permissions for Lambda and API Gateway
- Amazon S3 (for static frontend hosting) : Host the frontend (HTML/JS form to submit URLs)

## Features

- Generate unique short URLs for long links
- Redirect from short URL to original
- Fully serverless and scalable
- Simple HTML + JavaScript frontend

## How It Works

1. Frontend sends a long URL to API Gateway
2. Lambda generates a short code, save and fetch original URLs (in memory)
3. Redirects via the short code are also handled by Lambda

## Technologies Used

- AWS Lambda (Python)
- Amazon API Gateway
- Amazon S3 (Static Hosting)

---


