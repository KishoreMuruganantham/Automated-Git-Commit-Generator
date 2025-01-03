# 🚀 Automated Git Commit Generator  

Easily create and push multiple git commits with custom dates! This script is perfect for simulating commit histories or testing repositories.  

---

## ✨ Features  

- 📅 **Custom Commit Dates**: Generate commits with randomized months and days.  
- 📝 **Automatic Changes**: Adds changes to a `test.txt` file for each commit.  
- 🔗 **Push to Remote**: Automatically pushes commits to your repository.  

---

## 📋 Requirements  

- 🐍 Python 3.x  
- 🔧 Git installed and configured  

---

## ⚙️ Setup  

1. **Install Python 3.x**  
   - Check your version: `python --version`  
   - [Download Python](https://www.python.org/) if not installed.  

2. **Install and Configure Git**  
   - Verify Git installation: `git --version`  
   - [Download Git](https://git-scm.com/) if missing.  
   - Set up your Git profile:  
     ```bash
     git config --global user.name "Your Name (Eg: Kishore_M)"
     git config --global user.email "your.email@example.com (Eg: ABCD@gmail.com)"
     ```  

3. **Prepare Your Repository**  
   - Clone your repository:  
     ```bash
     git clone <repository-url>
     cd <repository-directory>
     ```  
   - Add the script (`app.py`) to the repository directory.  

---

## 🚴‍♂️ Usage  

1. **Run the Script**  
   ```bash
   python app.py
   ```  
   
2. **Follow Prompts**  
   - Enter the number of commits to create.  
   - Enter the year for commit timestamps.  

3. **What Happens Next?**  
   - The script generates a `test.txt` file.  
   - Creates the specified number of commits with custom dates.  
   - Pushes the commits to your remote repository.  

---

## 🛠 Example  

```bash
Enter the number of commits to create: 10  
Enter the year for the commits (e.g., 2024): 2024  
```  

The script will create **10 commits** with randomized dates in **2024** and push them to the **main branch**.  

---

## ⚠️ Notes  

- Ensure your branch name matches the script (`main` by default).  
- Update the branch in the script if needed:  
  ```python
  os.system('git push -u origin <branch-name>')
  ```  

---

## 🛑 Disclaimer  

- This script is intended for **personal and testing purposes only**.  
- Avoid using it to manipulate commit histories in shared or production repositories as it can lead to data inconsistencies and potential repository corruption.  
- Always verify changes before pushing them to any remote repository.  

---

## 👤 Author  

**Kishore Muruganantham**  
- GitHub: [KishoreMuruganantham](https://github.com/KishoreMuruganantham)  



## 📜 License  

This project is licensed under the **Apache License 2.0**.  
You may obtain a copy of the license at:  
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)  
