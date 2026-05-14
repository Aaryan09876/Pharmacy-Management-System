# Pharmacy-Management-System
The Pharmacy Management System is a console-based Python application designed to digitize and simplify daily operations of a medical store. 
It helps pharmacists manage medicine inventory, billing, sales records, and expiry tracking in one place. The system reduces manual errors in stock calculation, prevents sales of expired drugs, and generates bills instantly, making the pharmacy workflow faster and more reliable.
Core modules include medicine inventory management, customer billing, sales tracking, and admin controls. Pharmacists can add new medicines with batch number, quantity, price, and expiry date.
The system auto-updates stock after each sale and shows alerts for medicines nearing expiry or low in quantity. Billing module calculates total cost with GST, applies discounts, and prints a formatted invoice. 
Admin login allows viewing daily sales reports, searching medicine by name or salt, updating prices, and deleting expired stock. Input validation prevents negative stock entries and invalid dates.
All medicine records include MedicineID, Name, Quantity, Price, ExpiryDate, BatchNo. Before every sale, the system checks if stock >= quantity and expiry_date > today. 
Expired medicines are automatically blocked from billing. Sales transactions are logged with BillNo, Date, CustomerName, TotalAmount for audit purposes.
