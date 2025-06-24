# Company-ID-CARD-Generator
# PROJECT LOGIC:
-It is a form we can fill details of company and emp details to issue an id.
-U can select company it display company name and logo.
-Here i save 2 codes of html company id card.

# PROJECT IDEA:
This idea came from seeing so many company having id's then u can also create own company id card.

🪪 ID Card Generator

A simple multi-step form web application that collects employee details and generates a professional-looking ID card. The generated ID card can be downloaded as a PNG image or PDF file.

🔧 Features

• Multi-step form UI (Company Info → Employee Basic Info → Additional Info)
• Live preview of the generated ID card
• Auto-load company logos for popular companies (Amazon, Google, TCS, etc.)
• Upload and preview employee photo
• Download the ID card as: 
• PNG image
• PDF document
• Option to go back and edit form data

🖼️ Demo Preview

(![Company id-card](https://github.com/user-attachments/assets/fcd24b42-20b6-4684-945f-bc18d61c50df))

📁 Project Structure

• Id-cardgenerator.html: Main HTML file with inline CSS and JavaScript
• Uses CDN libraries: 
• html2canvas for capturing DOM as image
• jsPDF for PDF generation

🚀 How to Use

• Open Id-cardgenerator.html in any modern browser.
• Fill in all 3 steps of the form: 
• Company Info (Name, Logo)
• Employee Basic Info (Name, Position, Photo)
• Additional Info (DOB, Contact, Email, etc.)
• Click Submit to preview the ID card.
• Use the Download Image or Download PDF buttons to save the ID.
• You can click Edit to make changes.

🏢 Supported Company Logos

Just type the company name exactly as below to auto-load their logo:

amazon, flipkart, tcs, infosys, wipro, google, microsoft, accenture 

📦 Dependencies (via CDN)

<script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script> <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script> 

📜 License

This project is open-source and free to use for learning or personal projects.
