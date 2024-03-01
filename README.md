# Introduction

Hello,

Thanks for taking the time to complete this brief take-home assignment. It should not take more than 3 hours to finish.

The goal of this exercise is to evaluate your backend skills in developing lean microservices in JavaScript (Node.js, ExpressJS, 3rd-party integration, and testing). Feel free to make any assumptions, simplifications, or other changes to the problems - though please state those in your write up when you submit this assignment.

Using Express.js you will create a RESTFUL API to retrieve countries based on its currencies.

Before getting started, please read this document carefully.

# Acceptance Criteria

- API must follow REST standards and only allow one thing:

  1. Allow users to pull back all country names based on the oficial currency used by the country. 

- All endpoints must be behind HTTP Bearer Authentication. Use the following credentials, hardcoding a valid token on the backend: `15479a21-7d3a-4f5c-951d-c4e608d257f9`
- Code must be tested using the framework of your choice
- Document design decisions

## Example

Input: User sends `currency=usd`;

Output: List of countries using `usd` as oficial currency.

# What counts?

- All functional requirements must be satisfied
- Production-like code that must be well coded, clean, and commented
- Tests must be passing and meaningful
- General Node.js knowledge

# Submission

Once you're satisfied with what you've built. Publish your test as a public repository on your personal github and send us the link.

Please, avoid mentions to Pipfarm company in your test.

# Getting started

## What will you find inside this boilerplate

In this boilerplate, you will find:
- The main entry file: `index.js`
- A `README.md` file to document your comments and design decisions
- Inside the `package.json`, we added the following packages:
    - `express`

# Countries API

As a countries database, you can use the *REST Countries API*. The API provides basic information for countries based on different inputs. The API is open to the public and has no authentication requirements. See documentation for more information.

https://restcountries.com/
