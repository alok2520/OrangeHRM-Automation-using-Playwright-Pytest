# OrangeHRM-Automation-using-Playwright-Pytest
🚀 **OrangeHRM_Automation**  
🧪 *Portfolio demo automation project*

📚 **Tech Stack:**  
- `Playwright` 🎭  
- `PyTest` 🧪  
- `Python` 🐍  

🏗️ **Design Patterns Implemented:**  
- `POM` (Page Object Model) 🧩  
- `PyTest Fixtures` 🔧  

📁 **Test Data Mgmt:**  
🗄️ JSON-backed datastore: `src/tests/test_data/user_data.json`  
🔀 Dynamic runtime injection via CLI flag:  
```bash
pytest --datafile=[path]/[data-file-name]
```
📌 *Example:*  
```bash
pytest --datafile=src/tests/test_data/user_data.json
```

🐞 **Debugging Capabilities:**  
- `Playwright Trace Viewer` 🎥 (session recording)  
- Strategic logger instrumentation 📍 at critical execution checkpoints  

⚙️ **Test Execution Orchestration:**  
📍 *Precondition:* Ensure shell context is in project root directory 📂  
▶️ **Run command:**  
```bash
make [suite-name]
```
📌 *Example:*  
```bash
make sanity-tests
```
