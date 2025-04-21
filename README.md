# Excel Combiner Script

A simple Python script to merge multiple Excel files (`.xlsx`) with similar table structures into a single unified Excel workbook.

---

## 📌 Features
- Combines multiple `.xlsx` files from a specified folder
- Skips header rows from individual files and adds a unified header
- Outputs a single workbook with merged data

---

## 🛠 Requirements

Install required package using pip:
```bash
pip install openpyxl
```

---

## 🚀 Usage

1. Clone the repository:
```bash
git clone https://github.com/shreyash0019/excel-combiner-script.git
cd excel-combiner-script
```

2. Run the script:
```bash
python combine_excel_files.py
```

3. Follow the prompts:
   - Enter the name of the unified Excel workbook (e.g., `merged.xlsx`)
   - Enter the path to the folder containing `.xlsx` files to merge

---

## 📄 Example

If you have a folder with files:
```
data/
├── file1.xlsx
├── file2.xlsx
├── file3.xlsx
```

And each file contains a similar table structure, running the script will produce:
```
merged.xlsx
```
With all rows combined under unified headers.

---

## ✏️ Customization

You can modify the `headers` list in the script to match your specific column titles:
```python
headers = ['Nume', 'Prenume', 'Titlu', 'Editura', 'Cota', 'Pret', 'An']
```

---

## 📂 File Structure
```
excel-combiner-script/
├── combine_excel_files.py
├── README.md
```

---

## 📬 Contributing
Pull requests are welcome! Feel free to open issues or suggest features.

---

## 📄 License
This project is licensed under the MIT License.

---

Made with ❤️ by [Shreyash](https://github.com/shreyash0019)

