# 🔐 PassPass

**Generate strong, deterministic passwords from natural phrases — processed with reversible logic (ROT-N + enhancements) — usable online, offline, or even with pen and paper.**

## ✨ Why PassPass?

PassPass is a privacy-first tool built for security-conscious travelers, creators, and anyone who needs access to complex passwords — **without storing them anywhere**.

- 🚫 No local storage
- ✅ Fully offline, works in-browser
- 🔃 Reconstructable by hand if needed
- 🧠 Designed to live in your memory, not in a vault

## 🛠 How It Works

1. You input a familiar phrase like:

My favorite ice cream is Erdbeer Eis!


2. Set a **ROT-N** transformation number (like `7`)
3. The tool:
    - Applies a Caesar cipher (ROT-N) to A–Z/a–z letters only
    - Keeps all non-alphabet characters intact (`0-9`, `!@#$`, emoji, etc)
    - Removes spaces
    - Reverses the string

4. 🎯 You get the **output password**, which will _always_ be the same given the same input + ROT value.

## 🔒 Example

> **ROT**: 5  
> **Passphrase**:  
> `Ice cream in Vienna is awesome!`

> 🔑 **Output**:  
> `!jtrjxbtNXNfnnsnjHTZHVjhj`

## 💻 Usage

- Download the latest [`passpass.html`](./passpass.html)
- Open in any browser (online or offline)
- Type your ROT number + phrase
- Click “Transform” — and optionally “Copy to Clipboard”

## 🧠 Manual Reconstruction (No Computer Needed)

PassPass is designed so you can decode your own password **manually** if needed:

1. Apply Caesar shift (A–Z or a–z) letter-by-letter
2. Remove spaces
3. Reverse the result

This gives you **full access** even if you only have a pencil and memory.

---

## 📎 License

Released under the [Apache License, Version 2.0](LICENSE)

---

💡 Want to learn more about why this tool was created?  
Read the [companion blog post](https://ernstrenner.com/members/passpass-a-robust-password-generator-for-people-on-the-move/).

