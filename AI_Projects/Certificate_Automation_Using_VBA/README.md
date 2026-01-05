# Certificate Automation Using Excel VBA

## Project Description
This project automates certificate generation using a macro-enabled Excel file.
The Excel file contains embedded VBA code along with a button that allows users
to generate certificates automatically using a Word template.

On clicking the “Generate Certificate” button, the user selects the certificate
template and the destination folder. The macro dynamically replaces placeholders
in the Word document with candidate details from Excel and generates individual
PDF certificates for each candidate.

## Workflow
1. User clicks the “Generate Certificate” button in Excel
2. Selects the Word certificate template
3. Selects the destination folder
4. VBA replaces placeholders with candidate data
5. Certificates are generated automatically in PDF format

## Key Features
- One-click certificate generation
- Excel–Word integration using VBA
- Dynamic replacement of candidate name, date, and certificate ID
- Bulk certificate generation without manual effort
- Automatic file naming based on Candidate ID

## Tools Used
- Microsoft Excel (.xlsm)
- VBA (Visual Basic for Applications)
- Microsoft Word Automation

## Note
Only one sample certificate PDF is included in the repository for demonstration.
The actual automation generates certificates for all candidates dynamically.
