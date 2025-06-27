# 📝 Notecraft

**Notecraft** is a lightweight and efficient Java-based writing tool. It offers a distraction-free interface for creating and editing plain text, enhanced with a clean and modern look powered by **JTattoo**. Built using **Swing** and **AWT**, it runs smoothly on any system with Java installed.

---

## ⚙️ Features

- 🧾 Create, open, and save plain text files  
- ✍️ Font customization menu  
- 🎨 Clean and consistent UI with JTattoo styling  
- 🖥️ Built using Java's native Swing and AWT  
- ⚡ Fast, responsive, and portable  

---

## 🚀 Getting Started

### Requirements

- Java JDK 8 or higher  
- Any Java-compatible IDE or command line environment  

---

### 🔧 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/AshmitDas19/Notecraft.git
   cd Notecraft
   ```

2. **Compile the project**
   ```bash
   javac -cp "lib/JTattoo-1.6.13.jar" src/*.java
   ```

3. **Run the application**
   ```bash
   java -cp "lib/JTattoo-1.6.13.jar:src" App
   ```

> On Windows, replace `:` with `;` in the classpath:
```bash
java -cp "lib/JTattoo-1.6.13.jar;src" App
```

---

## 📁 Project Structure

```
Notecraft/
├── .idea/
│   ├── .gitignore
│   ├── misc.xml
│   ├── modules.xml
│   └── vcs.xml
├── lib/
│   └── JTattoo-1.6.13.jar
├── src/
│   ├── App.java
│   ├── FontMenu.java
│   └── NotecraftGUI.java
├── .gitignore
├── Notecraft.iml
└── README.md
```

---

## ❓ FAQ

**Q: Can I open and save text files?**  
A: Yes! You can load existing files and save new ones via the file menu.

**Q: Can I change the font?**  
A: Absolutely! Use the built-in font customization options.

**Q: Is it portable?**  
A: Yes, it runs anywhere Java is supported.

---

## 🤝 Contributing

You're welcome to contribute:

1. Fork the project  
2. Create a branch: `git checkout -b feature-name`  
3. Commit your changes  
4. Push and open a pull request  

---

## 📜 License

Licensed under the [MIT License](LICENSE).

---

## 💬 Contact

Have feedback or suggestions? Feel free to [open an issue](https://github.com/AshmitDas19/Notecraft/issues) or contribute!  
Built with ❤️ using Java.