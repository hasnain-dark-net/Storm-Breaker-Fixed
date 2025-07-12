# ⚡ Storm Breaker – Fixed Version (No Root Required)

This repository contains a clean, virtualenv-based, no-root-required version of Storm Breaker.  
✅ Safe for use on Kali, Ubuntu, Parrot OS  
✅ Runs via `st.py`  
✅ Uses Python 3+ virtual environment  

Made with 💻 by Hasnain Dark Net

---

<details>
<summary><strong>📦 Step 1: Clone the Repository</strong></summary>

<br>

```bash
git clone https:https://github.com/ultrasecurity/Storm-Breaker.git
cd Storm-Breaker
```

</details>

---

<details>
<summary><strong>🧪 Step 2: Create & Activate Virtual Environment</strong></summary>

<br>

```bash
python3 -m venv venv
```

📌 Har dafa tool chalane se pehle virtualenv activate karna zaroori hai:

```bash
source venv/bin/activate
```

</details>


---

<details>
<summary><strong>⚙️ Modified install.sh File</strong></summary>

<br>

### ✅ Modified `install.sh` (No Root Required – Safe for GitHub)

---

### 📌 How to Use:

1. Open terminal in `Storm-Breaker-Fixed/` directory
2. Run:

```bash
nano install.sh
```

3. Replace everything with the modified script above  

```bash
#!/bin/bash

echo ""
echo "              --      --"
echo "            .:\"  | .:'\" |"
echo "          --  ___   ___  -         Storm-Breaker's dependencies installer"
echo "        /:.  /  .\\ /.  \\ .\\"
echo "       |:|. ;\\___/O\\___/  :|  Github: https://github.com/ultrasecurity/Storm-Breaker/"
echo "       |:|. |  \`__|__'  | .|"
echo "       |:|.  \\_,     ,_/  /"
echo "        \\______       |__/"
echo "         |:.           \\"
echo "        /.:,|  |        \\"
echo "       /.:,.|  |         \\"
echo "       |::.. \\_;_\\-;       |"
echo " _____|::..    .::|       |"
echo "/   ----,     .::/__,    /__,"
echo "\\_______|,...____;_;_|../_;_|"
echo ""

# Update system packages (optional)
sudo apt update -y

# Install system dependencies (optional)
sudo apt install -y python3 python3-pip php

# Install Python packages (virtual environment only)
if command -v pip > /dev/null; then
    pip install requests pyngrok
else
    echo "pip not found. Please activate your virtual environment before running this script."
    exit 1
fi

echo ""
echo "[✔] All dependencies installed successfully."
```


4. Save and exit:
   - Press `Ctrl + O`, Enter  
   - Then `Ctrl + X`

✅ Done! Now run `./install.sh` safely without breaking your system.

</details>

---

<details>
<summary><strong>🧰 Step 3: Install Required Python Modules</strong></summary>

<br>

```bash
./install.sh
```

✅ This script installs all modules (requests, pyngrok, etc.) inside the virtualenv safely.

</details>

---
<details>
<summary><strong>📜 Optional: Install via requirements.txt</strong></summary>

<br>

If you prefer a single command install using a requirements file, run:

```bash
python3 -m pip install -r requirements.txt
```

✅ This will install all required Python modules (e.g. requests, pyngrok) in one go.

</details>

---

<details>
<summary><strong>🚀 Step 4: Run the Tool</strong></summary>

<br>

```bash
python3 st.py
```

</details>

---


<details>
<summary><strong>📂 Included Files</strong></summary>

<br>

```
st.py              ➤ Main launcher file  
install.sh         ➤ Safe installer script  
README.md          ➤ Full step-by-step guide  
.gitignore         ➤ Avoids uploading venv/__pycache__
```

</details>

---

<details>
<summary><strong>⚠️ No Root Required</strong></summary>

<br>

✅ This version runs entirely inside a Python virtual environment.  
❌ No system-wide pip installs  
❌ No sudo required for Python packages  

Best for ethical hacking demos, CTFs, and YouTube tutorials.

</details>

---

<details>
<summary><strong>🙌 Credits</strong></summary>

<br>

Modified & Repackaged by **Hasnain Dark Net**  
📺 Subscribe, ⭐ Star this repo, and share it with friends!

</details>
