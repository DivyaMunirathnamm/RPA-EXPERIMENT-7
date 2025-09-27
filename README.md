# RPA-EXPERIMENT-7
# NAME : DIVYA M
# REG NO : 212223040043
# AIM:
To create a UiPath workflow that reads and extracts text from a PDF file and saves the extracted content into a plain text file.

# ALGORITM:
Step 1: Create a New Process Open UiPath Studio and create a new process named PDFTextExtractor.

Step 2: Install PDF Activities (If Needed) Go to Manage Packages → Official → Search for UiPath.PDF.Activities.

Install and save.
Step 3: Add Variables Create the following variables:

Name Type Default Value (if any) pdfPath String "C:\Users\YourName\Documents\Sample.pdf" textData String (leave blank) textPath String "C:\Users\YourName\Documents\Output.txt"
Step 4: Add Read PDF Text Activity Drag and drop the Read PDF Text activity from PDF Activities.

Set the properties:
FileName: pdfPath
Output: textData
Enable Preserve Formatting (optional)
Step 5: Write Text to File Drag and drop Write Text File activity.

Set the properties:
FileName: textPath
Text: textData
Encoding: UTF-8 (optional)

# PROGRAM:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/8b09a64c-0731-4623-8523-8cb06004cbce" />


# OUTPUT:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/74a216c2-a286-40e1-8a96-6b1faff63957" />

# RESULT:
The UiPath workflow successfully reads the content from a PDF file and writes it into a .txt file using built-in PDF and File activities.
