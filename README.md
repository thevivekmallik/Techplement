# Real-Time Currency Converter

Welcome to the Real-Time Currency Converter! This simple Java console application allows you to convert currencies and manage your favorite currencies.

## Features

1. **Show Exchange Rates:** View the latest exchange rates for various currencies.
2. **Add Favorite Currency:** Add your favorite currencies for quick access.
3. **Show Favorite Currency:** Display a list of your favorite currencies.
4. **Update Favorite Currency:** Modify your list of favorite currencies.
5. **Delete Favorite Currency:** Remove a currency from your favorites.
6. **Exit:** Terminate the application.

## Getting Started

### Prerequisites

- Java Runtime Environment (JRE)
- Internet connection (for fetching real-time exchange rates)
- Jackson jar file ( jackson-databind-2.17.0, jackson-core-2.17.0, jackson-annotations-2.17.0)

### How to Run

1. Clone the repository.
2. Compile and run `CurrencyConverterApp.java`.
3. Follow the on-screen instructions to use the application.

## Usage

- When prompted for a currency code, enter the 3-letter currency code (e.g., USD, EUR).
- Favorite currencies are stored for future reference.

## Examples

### Show Exchange Rates

```java
Enter your choice: 1
Enter the amount: 1
Enter the source currency code: usd
Enter the target currency code: eur
1.00 USD is equal to 0.92 EUR

```java
Enter your choice: 2
Enter the currency code to add to favorites: gbp
GBP has been added to your favorite currencies.

```java
Enter your choice: 3
Favorite Currencies:
USD
EUR
GBP

```java
Enter your choice: 4
Enter the currency code to delete from favorites: eur
EUR has been removed from your favorite currencies.


Replace `https://www.exchangerate-api.com/` with the actual API name you used for exchange rates.
