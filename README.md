Billing Software  

Project Overview  
This is a desktop billing software application developed in Python with the Tkinter library. It simulates a retail Point-of-Sale (POS) system that processes transactions quickly and accurately. Users can select quantities of various products in three categories: Medical, Grocery, and Cold Drinks. The system calculates the total bill, including taxes, generates an itemized invoice, and manages sales records.  
Key Functionality  
• Customer Management: Input customer name and phone number.  
• Dynamic Billing: Automatically creates a unique 4-digit bill number for each transaction.  
• Sales Calculation: Computes the subtotal, taxes, and final bill amount based on entered quantities and fixed prices.  
• File Management: Bills are saved as text files for record-keeping.  
• Bill Retrieval: Enables searching and displaying previous bills using the unique bill number.  
• User Interface: A categorized GUI that makes item selection and data entry easy.  
________________________________________  
Features  
• Categorized Products: Items are divided into Medical, Grocery, and Cold Drinks sections.  
• Total Calculation: A dedicated button computes product totals and applied taxes instantly.  
• Itemized Bill Generation: Produces a clean, formatted bill in the central Bill Area.  
• Tax Application: Applies a tax percentage to each product category (e.g., Medical: 5%, Cold Drinks: 10%, Grocery: 500% - Note: The grocery tax rate of 5% seems unusual and should be checked in the code).  
• Clear Data Function: A button resets all quantity, price, and customer entry fields.  
• Persistent Storage: Saves generated bills as .txt files in a bills/ directory.  
________________________________________  
Technologies & Tools Used  
Category  Tool / Library  
Language  - Python 3.x  
GUI Framework  - tkinter (Standard Python library)  
Modules  - random (for bill number generation)  
System Interaction  - os (for file and directory operations)  
________________________________________  
Steps to Run the Project  
1. Prerequisites  
You need to have Python 3.x installed on your system. No external libraries are needed beyond the standard library modules (tkinter, random, os).  
2. Setup  
1. Save the Code: Save the provided Python code in a file named billing_app.py.  
2. Create Directory: In the same directory as billing_app.py, create a new folder named bills. This folder is necessary for saving and searching bills.  
   Bash  
   mkdir bills  
3. Execution  
Open your terminal or command prompt, navigate to the project directory, and run the script:  
   Bash  
   python billing_app.py  
The Tkinter GUI window will open, ready for use.  
________________________________________  
Instructions for Testing  
Follow these steps to test the application's core functions:  
1. Enter Customer Details: Fill in the Customer Name and Customer Phone fields in the top panel.  
2. Input Quantities: Enter numbers (e.g., 5, 10, etc.) into the entry fields for various products in the Medical, Grocery, and Cold Drinks sections.  
3. Calculate Totals: Click the Total button in the bottom panel.  
   o Expected Behavior: The fields for "Total Price" and "Tax" under all three categories should show calculated values.  
4. Generate and Save Bill: Click the Generate Bill button.  
   o Expected Behavior: The Bill Area (F5) should fill with the itemized bill, and a confirmation box will appear asking to save the bill. Click Yes.  
   o Verification: Check the bills/ directory. A new file named after the generated Bill Number (e.g., 1234.txt) should be created.  
5. Clear Data: Click the Clear button.  
   o Expected Behavior: All input fields should reset to 0 or blank, and a new random Bill Number should be generated.  
6. Find Bill:  
   o Enter the Bill Number you saved in Step 4 into the Bill Number search box.  
   o Click the Search button.  
   o Expected Behavior: The Bill Area should display the content of the saved bill file.  


Screenshots – 

