# C++ Project

# Health-Based Meal Suggestion System

This C++ console application provides personalized meal suggestions and health tips based on a user's age group and health conditions (e.g., diabetes, heart disease). It includes BMI calculations, nutritional information display, and an admin panel to view all registered users.

## 💡 Features

- **User Registration & Login**
- **Admin Login with User Data Viewing**
- **Health Issue-Based Meal Suggestions**
- **Age Group Categorization (Infant, Child, Teenager, Adult, Senior)**
- **BMI Calculation with Status Display**
- **Nutritional Recommendations Based on Health Issues**

## 🧑‍💻 Tech Stack

- **Language**: C++
- **Data Structures**:
  - `unordered_map` for user database
  - `list` for storing health issues

## 📋 Functionality Overview

### 👤 User
- Register with personal, health, and physical information
- Login to:
  - View BMI and corresponding health status
  - Get nutritional info based on listed health issues
  - Receive customized meal suggestions and health tips

### 🔐 Admin
- Login with hardcoded credentials
- View all registered user data

## 🏥 Health Issue Support
Meal and nutrition suggestions are currently available for:
- **Diabetes**
- **Heart Disease**

(Add more conditions in the future for expansion)

## 🔢 Age Group Classification
| Age         | Classification |
|-------------|----------------|
| < 2 years   | Infant         |
| 4–10 years  | Child          |
| 11–17 years | Teenager       |
| 18–64 years | Adult          |
| 65+ years   | Senior         |

## 🧮 BMI Categories
The system automatically calculates BMI and classifies into:
- Underweight
- Normal/Healthy Weight
- Overweight
- Obese


