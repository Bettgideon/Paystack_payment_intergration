# Mobile Money Payment Integration (M-Pesa & Airtel Money via Paystack)

## Overview
This project provides a seamless way to accept mobile money payments (M-Pesa and Airtel Money) in Kenya through the **Paystack** payment gateway.  
It offers a **responsive**, **secure**, and **user-friendly** form that collects essential payment details and processes transactions efficiently.

---


## Features
- ✅ Mobile money payment processing (M-Pesa and Airtel Money)  
- ✅ Responsive design (works on all devices)  
- ✅ Input validation for phone numbers and payment amounts  
- ✅ Automatic email generation if none is provided  
- ✅ Clear transaction feedback after payment  

---

## Setup Instructions

### 1. Prerequisites
- A [Paystack](https://paystack.com/) account
- A website where you want to integrate payments
- Basic knowledge of HTML and JavaScript

### 2. Integration Steps

#### Get your Paystack API Keys
- Log into your Paystack dashboard
- Navigate to **Settings > API Keys & Webhooks**
- Copy your **Public Key** (starts with `pk_...`)

#### Add the Code to Your Website
- Copy the entire HTML code from the provided file
- Paste it where you want the payment form to appear
- Replace the placeholder public key with your actual Paystack public key:
  ```javascript
  key: "pk_live_your_actual_public_key_here",
