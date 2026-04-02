# ISBN API 
Tamara Gitama
  SCT-254-031/2023

## Description
This project is a Python Flask API that:
- Computes ISBN-10 check digit
- Validates ISBN-10
- Converts ISBN-10 to ISBN-13
- Validates ISBN-13

## Endpoints

### 1. Compute Check Digit
POST /isbn10/check-digit

### 2. Validate ISBN-10
POST /isbn10/validate

### 3. Convert to ISBN-13
POST /isbn10/to-isbn13

### 4. Validate ISBN-13
POST /isbn13/validate

## Input Format (JSON)
Example:
```json
{
  "isbn": "0306406152"
}