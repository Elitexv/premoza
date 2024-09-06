# Premoza
An innovative real estate e commerce platform powered by Solana and Starknet, enabling users to,buy, rent or sell properties and book hotels from anywhere in the world with just one click.

we focusing on utilizing blockchain technology to help solve major real estate problems across the globe, seamlessly make payment for rental services and hotel booking using Premoza 


# Why Solana and Starknet

We are building our real estate e-commerce platform on both Starknet and Solana to leverage the unique strengths of each blockchain. Starknet offers the security and scalability of Ethereum through ZK-Rollups, ensuring that high-value real estate transactions are secure and cost-effective. Solana, with its high throughput and low transaction fees, allows us to provide a seamless, fast, and affordable user experience for real-time interactions and payments. By utilizing both blockchains, we can create a platform that combines the best of decentralization, security, scalability, and performance for our users.

## Pre-requisites
- XAMPP or mysql cli
- Node.js v20.^
- PHP v8.2.^
- Laravel v11.^ & Composer
  
## Setting up
- install dependecies
  ```
  composer install && npm install
  ```
- create environment
  ```
  cp .env.example .env
  ```
- generate app key
  ```
  php artisan key:generate
  ```
- launch xampp & start mysql
  > or use the mysql cmd line interface
- database migration
  ```
  php artisan migrate
  php artisan db:seed
  ```

## Start application
- start vite
  ```
  npm run dev
  ```
- start laravel
  ```sh
  php artisan serve
  ```

## Refresh migration
```
  php artisan migrate:refresh
  php artisan db:seed
```

## Refresh cache
```
  php artisan config:cache
```
