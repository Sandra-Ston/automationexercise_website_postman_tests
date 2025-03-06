
# Automation Exercise Website Postman Tests

## 📌 Overview

This repository contains Postman tests for the Automation Exercise website. These tests are designed to automate the testing process of various functionalities on the website.

## 📂 Contents

- `.github/workflows`: Contains GitHub Actions workflow files for CI/CD
- `AutomationExercise.postman_collection.json`: Postman collection file with test scenarios
- `Automation_Exercise.postman_environment.json`: Postman environment file with variables

## 🚀 Getting Started

1. Clone this repository
2. Import the Postman collection and environment files into Postman
3. Run the tests in Postman or use Newman for CLI execution

## ✅ Running Tests

### 1️⃣ Using Postman

1. Open Postman
2. Import the collection and environment files
3. Select the imported environment
4. Run the collection

###  2️⃣ Using Newman (CLI)

1. Install Newman:
   
```bash
npm install -g newman
```

2. Run the tests:
   
```bash
newman run AutomationExercise.postman_collection.json -e Automation_Exercise.postman_environment.json
```

## 🔄 CI/CD

This repository is set up with GitHub Actions for continuous integration. Check the `.github/workflows` directory for the workflow configuration.

## 📜 License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.

## 👩‍💻 Author

Sandra: [Github](https://github.com/Sandra-Ston)
