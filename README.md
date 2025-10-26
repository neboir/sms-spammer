# SMS Spawner (Educational Version)

⚠️ **Disclaimer:**  
This project is created **for educational and research purposes only**.  
Do **not** use it to spam, harass, or attack any real users or systems.  
The author and contributors are **not responsible** for any misuse of this tool.

---

## 📘 Description
This is a Python demo project showing how an SMS-sending loop *could* work in a controlled environment using **mock APIs**.  
It is intended for learning about:
- HTTP requests in Python  
- Loop execution and basic concurrency (threads or async)  
- API simulation and safe testing practices

This repository **does not** send real SMS messages. All network calls are mocked or intentionally printed to the console so you can learn without affecting real users.

---
## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/neboir/sms-spawner
2. Go to the project directory:
   ```bash
   cd sms-spawner
3. Install dependencies:
    ```bash
   pip install -r requirements.txt


## ▶️ Usage

Run the demo script:

python smsvip.py

You will be prompted to enter:

- A test phone number (example: 0987123456) — use only test or dummy numbers.  
- The number of iterations (example: 10) — how many times to run the mock send.

The script uses a mock sender by default (prints or calls a fake endpoint).  
No real SMS will be sent.
