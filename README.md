# X.com Clone 

A **UI-only** front-end clone of **X.com (formerly Twitter)** built using **HTML** and **TailwindCSS**.  
This project focuses entirely on replicating the layout and design of X.com without any backend or JavaScript functionality.

---

## 🚀 Features

- **Pixel-perfect UI Clone** – Matches the modern X.com interface.
- **Responsive Design** – Works seamlessly on mobile, tablet, and desktop.
- **Sticky Navbar** – Always visible for easy navigation.
- **Clean, Maintainable Code** – Well-organized and easy to edit.
- **TailwindCSS Styling** – Utility-first approach for rapid development.

---

## 🛠️ Technologies Used

- **HTML5** – Page structure and markup.
- **TailwindCSS** – Utility-first CSS framework for styling.
- **Node.js & npm** – For building TailwindCSS from `input.css`.

---

## 📂 Project Structure

   ```bash
   xcom-clone/
│── node_modules/ # Dependencies
│── src/
│ ├── input.css # TailwindCSS source file
│ ├── output.css # Compiled CSS file
│── index.html # Main HTML file
│── package.json # Project config & dependencies
│── package-lock.json # Dependency lock file
│── README.md # Documentation
   ```

---

## ⚡ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/ansh-tyagi11/xcom-clone.git
   cd xcom-clone
   ```

2. **Install dependencies**

   ```bash
   npm init -y
   ```

3. **Build TailwindCSS**
   ```bash 
   npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
   ```

4. **Open in Browser**

    Open index.html in your browser to view the UI.

---

**📜 License**
  
     This project is for educational purposes only.