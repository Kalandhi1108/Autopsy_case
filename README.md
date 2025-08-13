# Autopsy_case

OBJECTIVE - Autopsy is an open-source digital forensics tool designed to help investigators efficiently collect, analyze, and recover digital evidence from storage media. It enables the examination of file systems, recovery of deleted files, extraction of artifacts like browser history and emails, timeline creation, and generation of court-admissible reports, making it useful for cybercrime, fraud, and incident investigations.

STEP 1 – Get a Sample Evidence File from digitalcorpora 
   example evidence - nps-2008-jean.E01 and nps-2008-jean.E02

   
STEP 2 – Create a New Case
Open Autopsy.

Select Create New Case → Enter a Case Name and Base Directory (any folder where Autopsy will store results).

Click Next.

Step 3 – Add the Evidence File
Choose Add Data Source.

Select Disk Image or VM File.

Browse and select your .E01 or .dd file.

Click Next.

Step 4 – Select Ingest Modules
Enable common modules such as:

File Type Identification

Hash Lookup (optional, if you have hash sets)

Keyword Search

Extract Web Artifacts

Recent Activity

EXIF Parser

Click Finish to start processing.

Step 5 – Explore the Evidence
In the Tree View:

Data Sources → Browse file system structure.

Deleted Files → View and recover deleted items.

Extracted Content → Check browser history, emails, documents, chat logs.

Timeline → View chronological events.

Step 6 – Perform Searches
Use the Keyword Search to find terms (e.g., “password”, “confidential”).

Use Hash Lookup to identify known files.

Step 7 – Export & Report
Select relevant files or artifacts → Right-click → Extract File(s).

Go to Tools → Generate Report → Choose HTML, CSV, or Excel format


