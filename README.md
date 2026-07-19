# SMS-Bomber
SMS-Bomber – A high‑performance, multi‑threaded OTP flooding tool for educational security testing. Supports 130+ Indian endpoints, 100 concurrent threads, live stats, and rotating user‑agents. Obviously Paid 

# 🔥 Features

· 130+ active OTP endpoints – covers major Indian services (e‑commerce, fintech, food delivery, ride‑hailing, travel, etc.)
· 100 concurrent threads – delivers hundreds of OTP requests per minute
· Smart retry + cooldown – automatically retries failed requests and temporarily skips unresponsive endpoints
· 200+ rotating user‑agents – dynamically generated to avoid fingerprinting
· Live console dashboard – real‑time counters for Sent, Failed, and Rate‑Limited with screen clearing
· Cross‑platform – Windows, Linux, macOS
· Single‑file – zero configuration, ready to run

---

# ⚡ Quick Start

```bash
# Clone the repository
git clone https://github.com/wlzbi-exe/SMS-Bomber.git
cd SMS-Bomber

# Install dependencies
pip install -r requirements.txt

# Run the tool
python bomber.py 9876543210
```

(Replace 9876543210 with the target 10‑digit Indian mobile number.)

If you omit the phone number, you will be prompted to enter it interactively.

---

# 📊 Live Stats Example

```
Target: 9876543210
    OTP-BOMBING -Stats
——————————
• Sent   1247
• Failed 89
• Error  12
——————————
BY @wlzbi-exe | github.com/wlzbi-exe
```

· Sent – successful OTP requests (HTTP 2xx)
· Failed – client/server errors or timeouts
· Error – requests hitting rate‑limits (HTTP 429)

---

# 🛠️ Configuration

You can adjust the following constants at the top of bomber.py:

Variable Default Description
THREAD_COUNT 100 Number of concurrent workers
STATS_REFRESH 0.5 Seconds between stats updates
MAX_RETRIES 2 Retry attempts on failure
TIMEOUT 15 HTTP request timeout (seconds)

---

# ⚠️ Disclaimer

This tool is intended for educational purposes and authorized security testing only.
Unauthorised use against any individual or service is illegal and violates terms of service.
The author (wlzbi-exe) assumes no liability for any misuse.
Always obtain explicit permission before testing.

---

# 🤝 Contributing

Contributions are welcome!

· Fork the repo
· Create a feature branch
· Submit a pull request

Please ensure your code follows the existing style and includes appropriate comments.

---

## 📜 License

Distributed under the MIT License. See LICENSE for details.

---

## 📬 Contact for purchasing the tool

```GitHub – wlzbi-exe```
``` Telegram – @rejerks```
