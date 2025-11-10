# 🌐 DNS_Solver  
**A self-help toolkit for IIT Delhi students to diagnose and fix Wi-Fi & DNS issues**  
*Created by Aman (IIT Delhi)*  

---

## 🧭 Overview  
**DNS_Solver** is an open-source project built to help students at **IIT Delhi** fix the most common campus network issue — when **internal IITD websites (like Moodle, Webmail, and E-academics)** stop loading, even though external sites like Google and YouTube work fine.  

**Cause:**  
A wrong DNS configuration (often set to public DNS like `8.8.8.8` or `1.1.1.1`) which cannot resolve IITD’s private internal domains (`10.10.x.x` network).  

**DNS_Solver** provides **clean, step-by-step solutions for Windows, macOS, and Linux**, with explanations and copy-ready commands — all inside one interactive webpage.  

---

## 🚀 Features  
- 🪟 **Windows**, 🍏 **macOS**, 🐧 **Linux** repair steps side-by-side  
- ⚡ One-click copy for all commands  
- 🧩 Explains the *why* behind the fix — not just the steps  
- 🌙 Sleek dark UI with IITD-inspired gradient  
- 📱 Fully responsive and offline-friendly  
- 🧠 Helps students understand IITD’s internal DNS system  

---

## 🧰 Tech Stack  
- **HTML5** — simple and clean structure  
- **CSS3** — dark modern design, gradients, responsiveness  
- **Vanilla JavaScript** — for tab switching and copy buttons  
- **No dependencies** — runs locally or online, lightweight  

---

## 📖 How It Works  
1. Detects if your device is using public DNS instead of IITD’s internal DNS (`10.10.x.x`).  
2. Guides you to reset DNS and IP configuration back to automatic.  
3. Verifies connectivity using `ping`, `curl`, and DNS checks.  
4. Teaches how to avoid this problem in the future.  

---

## 🧩 Directory Structure  

    DNS_Solver/
    ├── index.html        # The main web interface
    ├── README.md         # Documentation file
    └── assets/           # (optional) screenshots or icons

---

## 💡 Usage  

### Option 1 — Run Locally  
Simply open `index.html` in your browser.  
No installation or dependencies required.  

### Option 2 — Host on GitHub Pages  
1. Push your repository to GitHub.  
2. Go to **Settings → Pages → Source → Deploy from branch**.  
3. Select the `main` branch and `/ (root)` folder.  
4. Your site will be live at:  

       https://<your-username>.github.io/DNS_Solver/

---

## 🧠 Example Use Case  
**Problem:** IITD Wi-Fi connected but `moodlenew.iitd.ac.in` won’t open.  
**Fix with DNS_Solver:**  
- Visit the web page.  
- Select your OS (Windows / macOS / Linux).  
- Copy and run the suggested commands.  
- DNS auto-reset → IITD sites accessible again ✅  

---

## 🧩 Future Roadmap  
- [ ] Auto-detect OS and DNS config  
- [ ] One-click “Fix Now” using PowerShell / Bash  
- [ ] Add IITD-specific modules (LDAP, VPN tests)  
- [ ] Mobile-optimized interface for hostel Wi-Fi debugging  

---

## 🧑‍💻 Author  
**Aman**  
B.Tech, Mechanical Engineering  
Indian Institute of Technology Delhi  

---

## ⚖️ License  
Released under the **MIT License** — free to use, modify, and share.  
Please retain attribution if redistributing.  

---

> *“A network issue shouldn’t block your learning. With DNS_Solver, it won’t.”* 🚀  
