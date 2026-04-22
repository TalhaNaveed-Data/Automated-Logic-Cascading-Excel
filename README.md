🔄 Automated Logic Cascading System
💡 Why I Built This?
I wanted to explore how formulas can create a "chain reaction" in data. This project demonstrates how a single input change can automatically update multiple tables based on specific mathematical rules. This is a core concept in creating efficient, error-free automated dashboards.
✅ What I Did:
Master Table Control: The first table serves as the primary input. Changing its value automatically updates all multiplication results within that table.
Absolute Referencing: Used Absolute Cell References such as (=$H$5) in the second table to lock onto specific values, ensuring the logic remains consistent even when data is moved.
Sequential Logic Linking: The third table is connected to the second using a dynamic formula like (=H5+1). This means Table 3 always stays one step ahead of Table 2 automatically.
Cascading Updates: Table 4 is linked to Table 3 in the same way, creating a complete flow where a single change in one part of the sheet ripples through all four tables instantly.
🛠️ Tools Used:
Microsoft Excel (Absolute Referencing, Logical Linking, Sequential Formulas, Table Formatting).
