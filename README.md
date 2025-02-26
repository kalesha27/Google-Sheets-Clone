# Google Sheets Clone  

## Overview  
This project is a **web-based spreadsheet application** that mimics the core functionalities of Google Sheets. It enables users to input, edit, and perform basic calculations in a tabular format.  

## Features  
- **Cell Editing** – Users can input and modify text/numbers in cells.  
- **Basic Formulas** – Supports simple arithmetic operations (e.g., `=A1+B1`).  
- **Row & Column Operations** – Add or delete rows/columns dynamically.  
- **Data Persistence** – Stores data temporarily using LocalStorage.  

## Tech Stack  
- **Frontend**: HTML, CSS, JavaScript  
- **Storage**: LocalStorage (for temporary data retention)  

## Folder Structure  
```
spreadsheet-clone-main/
│── index.html        # Main HTML file for the UI
│── script.js         # JavaScript logic for handling user interactions
│── style.css         # Stylesheet for UI design
│── README.md         # Project documentation
```

## Installation & Usage  
### **1. Clone the repository**  
```sh
git clone https://github.com/your-username/spreadsheet-clone.git  
cd spreadsheet-clone  
```

### **2. Open the project**  
- Open `index.html` in a web browser to start using the spreadsheet.  

## Future Improvements  
- **Backend Integration** – Store data in a database like Firebase or MongoDB.  
- **Advanced Formulas** – Support for functions like `SUM()`, `AVERAGE()`, `VLOOKUP()`.  
- **Real-time Collaboration** – Multi-user editing using WebSockets.  
- **Export & Import** – Save spreadsheets as `.csv` or `.xlsx` files.  
- **Cloud Deployment** – Host on AWS, Vercel, or Netlify.  

## License  
This project is licensed under the **MIT License**.  
