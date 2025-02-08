# CoreX-Recipe 🚀

## 📌 Overview  
CoreX-Recipe is a **txAdmin Recipe** that provides an **automated installation** for the **CoreX Framework** on a FiveM server. It ensures a **clean, structured, and hassle-free deployment** by downloading and configuring CoreX along with its required dependencies.

---

## 🔹 Features  
✅ **Automated CoreX Installation via txAdmin**  
✅ **Database Import for seamless setup**  
✅ **Includes `oxmysql` for database management**  
✅ **Pre-configured folder structure for FiveM scripts**  
✅ **Optimized for FiveM Build `3407`**  
✅ **Automatic cleanup of temporary files**  

---

## 📥 Installation Guide  

### **1️⃣ Deploy via txAdmin**  
1. Open **txAdmin** on your FiveM Server.  
2. Navigate to **"Recipe Deployer"**.  
3. Click **"Deploy Recipe from URL"**.  
4. Enter the **GitHub raw link** to `recipe.yaml`:  
   ```env
   https://raw.githubusercontent.com/LegacyAngel2K9/CoreX-Recipe/main/recipe.yaml
   ```  
5. Follow the on-screen instructions to complete the installation.

---

## 🔧 Configuration  

- The **CoreX Framework** will be installed inside:  
  ```
  ./resources/[CoreX]/CoreX/
  ```
- **Database Setup:**  
  The recipe will automatically import **CoreX database tables** into `oxmysql`.  
- **Standalone Dependencies:**  
  All required standalone scripts are placed inside:  
  ```
  ./resources/[StandAlone]/
  ```
- **Voice System:**  
  The `pma-voice` system is installed inside:  
  ```
  ./resources/[Voice]/
  ```

---

## 📜 License  
This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 🏆 Credits  
Developed by **Legacy DEV Team**  
Discord Server: [Discord Link](https://discord.gg/dayewa6xP6)  
For support, visit **[CoreX Documentation](https://docs.core-x.dev)**  