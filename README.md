# GitHub Follow Checker (Web App)

A clean, modern, and secure single-file web application to review, filter, and manage your GitHub connections (followers and following) directly from your browser.

🌐 **Live Web App:** [https://nagraggini.github.io/github-cleaner/](https://nagraggini.github.io/github-cleaner/)

---

## Features

* 🔍 **Follow Statistics:** Instantly lists users who are not following you back and those you haven't followed back yet.
* 🛡️ **Whitelist Protection:** Protect specific accounts from being unfollowed.
* 💾 **Local Storage:** Your username, token, and whitelist are automatically saved in your browser so you don't have to re-enter them.
* ⚡ **Direct Actions:** Unfollow accounts or follow them back with a single click.

---

## How to Get a GitHub Personal Access Token (PAT)

To use the web app, you need a classic GitHub Personal Access Token:

1. Log in to your [GitHub](https://github.com/) account.
2. Click on your **profile picture** in the top-right corner, then select **Settings**.
3. Scroll down to the very bottom of the left sidebar and click on **Developer settings**.
4. In the left sidebar, select **Personal access tokens**, then click **Tokens (classic)**.
5. Click the **Generate new token** button in the top right, and choose **Generate new token (classic)** (enter your password if prompted).
6. **Note:** Give it a descriptive name (e.g., `GitHub Follow Checker`).
7. **Expiration:** Choose an expiration period (or select *No expiration*).
8. **Scopes:** Scroll down the list and check the **`user`** checkbox (this automatically checks required sub-scopes like `user:follow` and `read:user`).
9. Scroll to the bottom and click the green **Generate token** button.
10. **Copy your token immediately!** GitHub will only show it to you once.

---

## How to Use

1. Open the live app: [https://nagraggini.github.io/github-cleaner/](https://nagraggini.github.io/github-cleaner/)
2. Enter your **GitHub Username**, **Personal Access Token**, and define your **Whitelist** (usernames separated by lines or commas).
3. Click **Load Data** to fetch your followers and following lists.
4. Manage your connections safely!
