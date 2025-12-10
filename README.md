<h1><b> CustomTkinter Calculator </b></h1>h1>

A modern, dark-themed calculator application built using Python and CustomTkinter (CTk).
This project includes basic arithmetic operations as well as additional scientific functions such as square root, log, percentage, and power.


---

🚀 Features

✔ Modern dark UI using CustomTkinter
✔ Clean layout styled like a mobile calculator
✔ Supports:

Addition, subtraction, multiplication, division

Percentage

Power ( ^ )

Square root ( √ )

Log base 10 (Log)
✔ Error handling (Division by zero, invalid input, etc.)
✔ Responsive button grid layout



---

📸 UI Preview

<img width="682" height="916" alt="Calculator" src="https://github.com/user-attachments/assets/da409cc8-82c0-409c-941a-d4b29d927e4a" />


---

📂 Project Structure

MiniProject.py   # Main application file (GUI + Logic)


---

🛠 Requirements

Install the required modules:

pip install customtkinter

Python's built-in math module is used for advanced calculations.


---

▶ How to Run

1. Clone the repository:



git clone https://github.com/your-username/your-repo-name.git

2. Open the folder:



cd your-repo-name

3. Run the program:



python MiniProject.py


---

🔧 Code Overview

CustomTkinter UI

The app uses:

CTkFrame for layout

CTkButton for buttons

StringVar for input/output

Grid system for auto-resizing


Calculation Logic

User input is captured in input_var.
Pressing "=" evaluates math expressions using Python’s eval() after formatting (^ → ** , % → /100).
Additional buttons use math.sqrt and math.log10.


---

🧑‍💻 Author
H Hapukotuwa
himahapukotuwa8219@gmail.com



---

📜 License

This project is licensed under the MIT License.
Feel free to use, modify, and distribute.
