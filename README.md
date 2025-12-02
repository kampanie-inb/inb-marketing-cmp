# INB Marketing CMP – Google Consent Mode v2 Template

This Google Tag Manager custom template enables full integration with Google Consent Mode v2, allowing websites to:

- set default consent states  
- update consent signals based on user choices  
- sync CMP cookie values  
- enable optional features such as **ads_data_redaction** and **url_passthrough**

The template is fully compatible with:  
✔ Google Consent Mode v2  
✔ Google Tag Manager Web Container  
✔ Any CMP that stores user choices in a JSON cookie  

---

## 🚀 Features

- Default consent setup per region  
- Reading CMP cookie (JSON format)  
- Automatic conversion of CMP settings to Consent Mode signals  
- Optional toggles for:
  - `ads_data_redaction`
  - `url_passthrough`
- Secure use of GTM Template APIs  
- No external scripts  
- No external dependencies  

---

## 📦 Installation

### 1. Import the template into Google Tag Manager

Go to:  
**Templates → Tag Templates → Import**  
Select **template.tpl**.

### 2. Configure fields

**Required:**
- CMP Cookie Name

**Optional:**
- Region-based default consent settings  
- Enable ads_data_redaction  
- Enable url_passthrough  

### 3. Add a trigger

Recommended trigger:  
**Initialization – All Pages**

---

## 📘 Documentation

Documentation page coming soon.

---

## 🏷 Categories (Google Template Gallery)

- TAG_MANAGEMENT  
- ANALYTICS  
- MARKETING  

---

## 📄 License

This project is licensed under the **Apache 2.0 License**.  
See the `LICENSE` file for details.
