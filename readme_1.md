It looks like your virtual environment (`venv`) is missing or the path is incorrect. Here’s how you can fix it:

### ✅ **Step 1: Check if `venv` Exists**
Run the following command in your project directory:
```bash
dir
```
or
```bash
ls
```
If you **don’t see a `venv` folder**, you need to create it.

---

### ✅ **Step 2: Create a New Virtual Environment**
If `venv` is missing, create one with:
```bash
python -m venv venv
```
Then activate it:

#### On Windows (Command Prompt):
```bash
venv\Scripts\activate
```

#### On Windows (PowerShell):
```powershell
venv\Scripts\Activate.ps1
```

#### On Mac/Linux:
```bash
source venv/bin/activate
```

---

### ✅ **Step 3: Install Dependencies**
After activation, install Django and other requirements:
```bash
pip install django
```

---

### ✅ **Step 4: Verify Virtual Environment**
Run:
```bash
where python
```
It should point to your `venv` directory.

Now, try running:
```bash
python manage.py runserver
```

Let me know if you face any issues! 🚀