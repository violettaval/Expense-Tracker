# Expense Tracker


## Description
Budget Tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline they populate the total when brought back online.

## Table of Contents 

* [Installation](#installation)

* [Usage](#usage)

* [Contributing](#contributing)

* [Tests](#tests)

* [Questions](#questions)

## Installation

To install necessary dependencies, run the following command:

```
npm i

```

## Usage

This is set of server scripts to run on a heroku hosted server to log expenses. Uses MongoAtlus database Hosting but also has incorporated indexdatabase caching so that it can work when offline. 

![1](https://user-images.githubusercontent.com/70643274/99329547-17f8ca80-2844-11eb-9356-0050c12f59e7.PNG)

The graph and table are very clean and easy to read. Tranaction are submitted with a name and amount with different buttons for adding and subtracting.

![2](https://user-images.githubusercontent.com/70643274/99329548-17f8ca80-2844-11eb-9c73-799ae5ae2885.PNG)

The app can be used offline or downloaded because a Manifest and Service Worker are included.

![3](https://user-images.githubusercontent.com/70643274/99329550-17f8ca80-2844-11eb-8358-0fdb42601f00.PNG)

Unsent submissions are store in a local indexed database.

## Contributing

A live version is hosted here demo here https://expencetrackr.herokuapp.com/ or visit the repo https://github.com/violettaval/Expense-Tracker

## Tests

To run tests, run the following command:

```
npm run test
```

## Questions

If you have any questions about the repo, open an issue or contact me directly at violetvalencia@gmail.com. You can find more of my work at [violettaval](https://github.com/violettaval/).

