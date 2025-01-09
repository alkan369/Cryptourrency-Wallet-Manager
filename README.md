# Cryptourrency-Wallet-Manager
Cryptocurrency wallet manager which provides the most basic operations like buy, sell, check wallet summary, etc.

## Project
The cryptocurrency wallet manager provides functionalities for:
* registration/login of a client
* deposit a given sum to the wallet
* buy and sell crypto
* check wallet summary

The system will communicate with a third-party REST api called [CoinAPI](https://docs.coinapi.io/#list-all-assets) from which live data(like current price in USD$) for the cryptocurrencies will be extracted.

## Purpose
The main purpose of the project is to gain experience with Java and Spring that would be useful for future development of my professional career

## Format of development in Github
Every feature/functionality of the project will be developed in a seperate branch named: feature/(feature-name) which will then be merged with the main branch through pull-request

## Development Plan
The project is planned to be made with Spring MVC with basic UI(only with HTML and simple CSS).

For database: Redis will be used for the third-party data that will be extracted from  CoinAPI and PostgreSQL will be used for the user data storage.

For later stages of development CI/CD may be added with dockerization and possible host in AWS.