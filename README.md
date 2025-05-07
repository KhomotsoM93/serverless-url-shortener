# Serverless-URL-Shortener

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [How It Works](#how-it-works)
- [Technologies Used](#technologies-used)

## Project Overview

A simple serverless application built using AWS services to shorten long URLs. This project demonstrates how to build a fully functional URL shortener using:

- AWS Lambda
- Amazon API Gateway
- Amazon DynamoDB
- Amazon S3 (for static frontend hosting)

## Features

- Generate unique short URLs for long links
- Redirect from short URL to original
- Fully serverless and scalable
- Simple HTML + JavaScript frontend

## How It Works

1. Frontend sends a long URL to API Gateway
2. Lambda generates a short code and stores it in DynamoDB
3. Redirects via the short code are also handled by Lambda

## Technologies Used

- AWS Lambda (Python or Node.js)
- Amazon API Gateway
- Amazon DynamoDB
- Amazon S3 (Static Hosting)
