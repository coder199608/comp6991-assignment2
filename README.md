<!-- GitHub banner / 微信二维码区域 -->
<p align="center">
  <img src="https://github.com/coder199608/pictures/blob/main/images/avatar.jpg" width="120" alt="avatar">
  <img src="https://github.com/coder199608/pictures/blob/main/images/wechat_qr.png" width="120" alt="WeChat QR" title="扫码加我微信">
</p>

<h1 align="center">🔥 6年全栈工程师 | 留学生编程导师 | 800+无差评</h1>

<p align="center">
  <em>🚀 Helping CS international students ace their assignments, projects, and careers.</em>
</p>

---

# RSheet: Collaborative Spreadsheet Server in Rust (COMP6991 Assignment 2)

📊 This repository outlines the design strategy and implementation insights for **COMP6991 Assignment 2 - RSheet**, a terminal-based, multi-user spreadsheet server developed in **Rust**.

> ❗ **Note:** Source code is not included to uphold academic integrity. If you're working on a similar assignment and need guidance on architecture or debugging, feel free to reach out.

---

## 🧠 Project Overview

RSheet is a command-line spreadsheet server that supports concurrent client interactions. Key features include:

- 🧮 **Cell Management**: Handle `SET` and `GET` commands to manipulate cell values.
- 🔁 **Expression Evaluation**: Support for arithmetic expressions and cell references.
- 🧵 **Concurrency**: Manage multiple client connections simultaneously.
- 📡 **Broadcasting**: Notify all clients of changes to the spreadsheet state.
- 🧾 **Logging**: Maintain a history of commands for auditing purposes.
- 🧼 **Resource Management**: Ensure proper cleanup of resources upon client disconnection.

The implementation emphasizes:

- **Modular Design**: Separation of concerns across different modules.
- **Thread Safety**: Utilize Rust's ownership model to prevent data races.
- **Robust Error Handling**: Gracefully handle invalid inputs and system errors.

---

## ✅ Test Results

All provided test cases have been successfully passed, including:

- `connect-basic`
- `set-get`
- `expression-evaluation`
- `concurrent-access`
- `broadcast-updates`
- `logging-commands`

---

## 💬 Need Assistance?

If you're encountering challenges with the RSheet assignment or need a walkthrough of the design and implementation process in Rust, I'm here to help.

📱 **Contact via WeChat: `coder199608`**

*Please note: I do not provide direct code solutions but am happy to assist you in understanding the concepts and debugging your implementation.*

---

## ⚠️ Disclaimer

This repository **does not contain** any source code to maintain academic fairness. Sharing or using assignment solutions directly is a violation of most university academic honesty policies.

---

## 📚 Tags

`Rust` `COMP6991` `RSheet` `Concurrency` `Spreadsheet` `Command-Line` `Server` `Assignment Help`
