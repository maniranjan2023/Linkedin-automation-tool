# 🔗 LinkedIn Automation Tools

A collection of browser-based automation scripts to help manage your LinkedIn connections and blocked members.

## ✨ Features

- ✅ **Connection Request Acceptor**  
  Automatically accepts all pending LinkedIn connection requests.

- 🚫 **Member Unblocker**  
  Automatically unblocks all members you've previously blocked on LinkedIn.

---

## 📦 Installation

Clone this repository using the following commands:

```bash
git clone https://github.com/yourusername/linkedin-tools.git
cd linkedin-tools

## 🚀 Usage

> 💡 **Note:** These scripts are intended to be run directly in your browser’s developer console while you are logged in to LinkedIn.

---

### 🔁 Accepting Connection Requests

1. Log in to your LinkedIn account.
2. Navigate to the [My Network](https://www.linkedin.com/mynetwork/invitation-manager/) page.
3. Open your browser's Developer Console:
   - Press `F12` or right-click → `Inspect` → select the `Console` tab.
4. Open `requests-acceptor.js` from the cloned repository.
5. Copy and paste the entire script into the browser console and press **Enter**.

#### ✅ What it does:
- Finds all pending connection requests.
- Automatically accepts them one by one.
- Waits 1 second between each action to avoid LinkedIn's rate limiting.
- Logs progress in the console.

---

### 🔓 Unblocking Members

1. Log in to your LinkedIn account.
2. Navigate to the [Blocked Members Settings](https://www.linkedin.com/psettings/blocked) page.
3. Open your browser’s Developer Console.
4. Open `unblock-all.js` from the cloned repository.
5. Copy and paste the entire script into the console and press **Enter**.

#### ✅ What it does:
- Identifies all blocked members.
- Clicks the unblock button for each one.
- Prompts for your password when required (you may need to modify the script).
- Waits between actions to reduce the risk of being rate limited.
- Logs progress in the console.

---

## ⚠️ Important Notes

- These scripts must be run in the **browser console**.
- Ensure you are **logged into LinkedIn** before running the scripts.
- Scripts include **delays** to mimic human behavior.
- **Use these tools responsibly** and ensure compliance with [LinkedIn’s User Agreement](https://www.linkedin.com/legal/user-agreement).
