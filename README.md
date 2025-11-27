# API Automation Testing with Newman

This repository contains an automated API testing framework built using **Postman** and executed through **Newman**.  
It is designed to improve test coverage, and ensure API reliability through structured test suites and detailed reporting.

This project also supports **dynamic data testing** using **CSV data files**, allowing data-driven test execution.

---

## 🚀 Features

- Automated execution of Postman collections 
- Supports positive, negative, functional, and integration test scenarios  
- Chained requests for end-to-end flow testing  
- Integrated reporting (HTML reports)  
- Easy to integrate with Jenkins, GitHub Actions, GitLab CI/CD, etc.

---

## 🧩 Installation

The easiest way to install Newman is using **NPM**.  
If you already have Node.js installed, simply run:

```bash
npm install -g newman
```

This installs Newman globally so you can run it from anywhere.

```bash
npm install -g newman-reporter-htmlextra
```
---

## 📊 Running With HTML Report

```bash
newman run <collection> -d <test case_file.csv> -r htmlextra --reporter-htmlextra-title "<newman_title>"  --reporter-htmlextra-browserTitle "<browser_title>"
```

---

## 🏗 Project Structure


