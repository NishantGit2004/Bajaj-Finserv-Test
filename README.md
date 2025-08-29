# VIT BFHL API – Node.js Solution

This is a ready-to-deploy solution for the VIT BFHL problem statement.  
It exposes a **POST** `/bfhl` endpoint that processes an array of strings and returns categorized results.

---

## 🚀 Features
- Accepts an array of strings in the request body.
- Returns:
  - `odd_numbers` (as strings)
  - `even_numbers` (as strings)
  - `alphabets` (uppercased)
  - `special_characters` (single non-alphanumeric symbols)
  - `sum` (numeric sum of numbers, returned as string)
  - `concat_string` (reverse alternating-caps concatenation of alphabetic characters)
- Includes user details from environment variables:
  - `user_id` → `full_name_ddmmyyyy`
  - `email`
  - `roll_number`

---


---

## ⚙️ Setup

### 1. Clone & Install
```bash
git clone <your-repo-url>
cd <your-repo>
npm install