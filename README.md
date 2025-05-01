# Bulk Car Style Analyzer 🚗📊

A desktop application built using **Python Tkinter** that enables users to analyze bulk car make and style data. With a user-friendly interface, it allows you to input data, view analysis results in a table, and export them to a CSV file.

---

## 🧰 Features

- Enter or paste car data in the format: `Make,Style`
- View a count of unique car makes and styles
- Load sample/example data for quick testing
- Export analyzed data to a `.csv` file
- Responsive UI with scrollable input and result areas

---

## 🖼️ Application Workflow

![Uploading ChatGPT Image May 1, 2025, 09_57_48 PM.png…]()

---

## 📦 Technologies Used

| Library       | Purpose                                       |
|---------------|-----------------------------------------------|
| `tkinter`     | GUI creation and event-driven interface       |
| `ttk`         | Themed widgets for a modern UI                |
| `scrolledtext`| Multi-line text input with scrollbar          |
| `csv`         | Exporting results to CSV format               |
| `filedialog`  | File-saving interface                         |

---

## 🛠️ How It Works

### 1. **Input Section**
- Enter data in the format: `Make,Style` (e.g., `audi,sedan`) — one entry per line.
- You can also load sample data using the **"Load Example"** button.

### 2. **Analysis**
- Click **"Analyze Data"** to count the frequency of each unique Make/Style pair.
- Results appear in a table on the right side of the app.

### 3. **Exporting**
- Once analysis is complete, click **"Export Results"** to save the data as a CSV file.

---

## 💻 UI Overview

- **Left Panel**: Text area to input or paste data.
- **Right Panel**: Table view of analysis results.
- **Bottom Bar**: Live status messages and export functionality.

---

## 📁 Example Input

```txt
alfa-romero,convertible
alfa-romero,hatchback
audi,sedan
bmw,sedan
```

---

## 🔧 Installation & Run

### Prerequisite
- Python 3.x

### Run the App

```bash
python With_GUI.py
```

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Contributing

Pull requests are welcome! Feel free to fork the project, make improvements, and submit a PR.

