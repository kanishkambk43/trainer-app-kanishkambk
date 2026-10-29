# Trainer App

A React Native mobile application built with Expo, featuring a multi-step data-entry flow and salary projection functionality.

## Overview

The Trainer App allows users to enter details for multiple people and view salary projections based on their current salary. It provides a structured input flow and displays results in individual cards.

## Features

- **Multi-Person Data Entry** — Enter details for 1–50 people.
- **Step-by-Step Forms** — Capture name, age, salary, current company, and target company.
- **Salary Projections** — Calculate a 10% salary increase for qualifying entries.
- **Salary-Based Guidance** — Display messages based on the entered salary.
- **Results Dashboard** — View individual salary details and projections.
- **Reset Functionality** — Clear the current session and start again.
- **Cross-Platform Development** — Built using React Native and Expo.

## Tech Stack

- **Framework:** React Native
- **Development Platform:** Expo
- **Language:** JavaScript
- **Navigation:** Expo Router (in applicable projects)
- **Package Manager:** npm

## Repository Structure

This repository contains multiple React Native and Expo examples:

- `Myapp/` — Expo Router starter application.
- `profile/` — Profile screen UI example.
- `routestandlayouts/` — Multi-person salary projection application.
- `tabview/` — Tab-based navigation example.

Each directory may represent a separate application with its own dependencies and configuration.

## Getting Started

### Prerequisites

Ensure you have installed:

- [Node.js](https://nodejs.org/)
- npm
- [Expo Go](https://expo.dev/go) or an Android emulator for testing.

### Installation

Clone the repository:

```bash
git clone https://github.com/kanishkambk43/trainer-app-kanishkambk.git
```

Navigate to the application directory you want to run. For example:

```bash
cd trainer-app-kanishkambk/Myapp
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npx expo start
```

Follow the terminal instructions to run the application on a compatible device or emulator.

### Run the Salary Projection App

From the repository root:

```bash
cd routestandlayouts
npm install
npx expo start
```

## Salary Projection Workflow

1. Enter the number of people whose details need to be recorded.
2. Enter each person's name, age, salary, current company, and target company.
3. Navigate through the forms using the Next button.
4. View the salary projections and contextual messages.
5. Reset the application to start a new session.

### Projection Rules

- Salaries above ₹1,000 receive a calculated 10% increase.
- Salaries greater than ₹0 and below ₹10,000 trigger additional company-change guidance.
- Entries without a name are excluded from the results.

These rules are application-specific demonstration logic and do not represent guaranteed salary increases or professional financial advice.

## Development

The application uses React Native components such as `View`, `Text`, `TextInput`, `TouchableOpacity`, and `ScrollView` to build its interface.

Useful Expo commands:

```bash
npx expo start
npx expo start --android
npx expo start --web
```

Available platforms depend on the project's configuration and local development environment.

## Project Status

The repository contains multiple mobile application examples and UI experiments. Features and configuration may differ between individual project directories.

## License

No license has been specified for this repository.
