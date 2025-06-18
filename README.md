# Calcula GPS Ajudante Salweb - Automatic CNIS Analysis Tool

## Primary Objective
This project aims to process "PRISMA/SABI Completo" and "Contribuições/Recolhimentos" PDFs to identify contribution issues (e.g., below minimum wage), suggest necessary actions (e.g., 11% to 20% complementation, MEI 5% to 20%, minimum complementation for codes 1007/1406), and automatically generate an HTML table. This table is formatted for upload into the  extension, facilitating automatic entry of competencies into Salweb.

## Key Features
- Analyzes CNIS to identify pending issues.
- Generates HTML for import into the  extension for automatic filling in Salweb.

## Target Audience
This tool is designed for INSS (National Social Security Institute) civil servants who need to calculate contribution value differences to input into Salweb and generate the GPS (Social Security Guide) for the insured.

## How to Use
1.  Use the provided prompt with the CNIS PDFs.
2.  Copy the generated HTML table.
3.  Paste the HTML into the  extension.
4.  Save the output as a  file for later import by the  extension.

## Requirements
-   A Large Language Model (LLM) to use the prompt.
-   The 'Ajudante Salweb' extension installed in Firefox.
-   The 'PRISMA/SABI Completo' PDF and the 'Contribuições/Recolhimentos' PDF.

## Limitations and Recommendations
This tool has been thoroughly tested multiple times, and values have been cross-checked both manually (using the rule of three) and by entering them into the CI spreadsheet, consistently yielding the same results. However, **each civil servant is responsible for their own work and must verify and check every interaction and entry.** The tool is an aid, but the final responsibility for the correctness and suitability of the work lies with the civil servant.

## Contact
For questions or suggestions, you can contact me via email: wanderleyamorim.com@gmail.com

## Additional Information
This process is highly useful and has saved me a significant amount of time, in addition to being less susceptible to failures, human calculation errors, filling mistakes, etc.
