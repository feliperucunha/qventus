# Qventus Frontend Test

An incomplete login page with the password field alone and it's validations

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running](#running)
- [Running the Tests](#running-the-tests)
- [Usage](#usage)
- [Explanation](#explanation)

## Getting Started

This React password input component allows users to input a password with validation checklist. Each requirement is customizable, and the checklist updates in real-time based on the entered password.

### Prerequisites

Before using this component, make sure you have Node.js and npm installed on your machine.

### Installation

To install the component, run the following command:

```bash
npm install
```

### Running

To run the project, run the following command:

```bash
npm start
```

## Running the Tests

To run the tests, run the following command:

```bash
npm test
```

## Usage

As it is right now, the project is ready to be used as intended, you enter the password and it is validated according to the data provided, but it can be customized by entering the '/src/pages/Login/index.js' file. You can swap states on the isActive prop or add more validations, you just need to enter the proper regex and text as the data is being mapped.

### Explanation

 - I'm using a random icon library, but any library or SVGs could be used to reach the same goal.
 - I'm using CSS as it is the purest form of styling and can be adapted to other forms, like: tailwind css, scss, chakra, etc.
 - I wanted to show agility while prioritizing code quality, so although the code is clean, there is one ugly part to achieve the stretch goal which is on /src/components/PasswordInput/index.js line 43. This is a point of improvement in the code.
 - This could also have been developed using Typescript, but again, I was trying to prioritize speed and setting up TS would take a lot of time.
 - Overall I really liked the project, it might seem simple at first, but it envolves a lot of important things.
