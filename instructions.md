### **🚀 PocketVPS**  
---
### **📌 Step 1: Install Required Packages**  
```sh
apt update && apt upgrade -y
```
```
pkg install openssh -y  
```

---

### **🔒 Step 2: Configure SSH Server**  
```sh
sshd # Start the SSH server  
```
```
passwd  # Set your SSH login password   
```

---

### **🌍 Step 3: Establish Remote Access**  
```sh
ssh -R <PORT>:localhost:8022 serveo.net  
```
🔹 Replace `<PORT>` with a **random 5-digit number** (e.g., 54321).  

---

### **💻 Step 4: Connect from Your Laptop/PC**  
```sh
ssh root@serveo.net -p <PORT>  
```
🔹 Use the **same port** set in Step 3.  

---
**🎭 Join the Community!**

💬 Need help? Have questions? Join my Discord server!

🔗 [Click Here to Join](https://dsc.gg/itz0cat)

🚀 PocketVPS – Bringing the Power of a VPS to Your Pocket!
