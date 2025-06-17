# 📄 Real-Time Collaborative Document Editor

A modern real-time collaborative document editor built with:
✅ **React.js** — Dynamic, responsive frontend
✅ **Node.js + Express** — Backend server with Socket.IO for real-time updates
✅ **MongoDB** — Document storage (string type field + save history)
✅ **jsPDF** — Download your document as PDF

---

## 🚀 Features

* Real-time editing across multiple users
* Seamless synchronization
* Save document versions to MongoDB
* Download current document as PDF
* Smooth UI with modern animations (no TailwindCSS)

---

## 🛠 Tech Stack

| Frontend | Backend           | Database |
| -------- | ----------------- | -------- |
| React.js | Node.js + Express | MongoDB  |
| jsPDF    | Socket.IO         | Mongoose |

---

## ⚡ Installation

```bash
# Clone this repository
git clone https://github.com/your-username/realtime-doc-editor.git
cd realtime-doc-editor

# Install frontend dependencies
npm install

# Move to backend folder (if separated) or install backend dependencies
# npm install (for server)

# Start client (React app)
npm start

# Start server
node server.js
```

---

## ⚙️ Configuration

👉 Create a `.env` file in your project root:

```
MONGODB_URI = Wrie yorr mongodb URL
PORT = 5000
```

---

## 📝 How to Use

1️⃣ Open `http://localhost:3000/`
2️⃣ Start typing — edits sync in real time
3️⃣ Use **Download PDF** to export your text
4️⃣ Use **Save to DB** to store your document (each save creates a new record)

---

## 📁 Project Structure

```
realtime-doc-editor/
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   └── Editor.js
│   │   ├── App.js
│   │   ├── App.css
│   │   └── index.js
├── server.js
├── models/
│   └── Document.js
├── package.json
├── .env
└── README.md
```

---


## ✨ Credits

Created by **Chhatrala Tirth**

---

## 📌 License

This project is licensed under the MIT License.

---
