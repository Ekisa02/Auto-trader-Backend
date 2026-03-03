# Auto Trader Backend

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation Instructions](#installation-instructions)
3. [Requirements](#requirements)
4. [Environment Setup](#environment-setup)
5. [Language and Framework Details](#language-and-framework-details)

## Project Overview
Auto Trader is a backend service that supports an online trading platform. It provides APIs for managing user accounts, trade processes, and real-time data fetching necessary for successful trading.

## Installation Instructions
To install and set up the Auto Trader Backend, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Ekisa02/Auto-trader-Backend.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Auto-trader-Backend
   ```

3. Install the required packages:
   ```bash
   npm install
   ```

## Requirements
- Node.js version 14 or higher
- MongoDB (local or hosted)
- Access to a command-line interface

## Environment Setup
1. Create a `.env` file in the root of the project.
2. Add the following environment variables (example):
   ```
   PORT=3000
   DATABASE_URL=mongodb://localhost:27017/autotrader
   JWT_SECRET=your_jwt_secret
   ```

3. Ensure MongoDB is running locally or change the database URL to your hosted MongoDB instance.

## Language and Framework Details
- **Programming Language**: JavaScript
- **Framework**: Node.js and Express for building APIs
- **Database**: MongoDB for data storage
- **Others**: JWT for authentication, Mongoose for ODM
