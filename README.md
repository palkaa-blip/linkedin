Schedule Trigger (Mon / Wed / Fri, 10 AM)
        |
   Config (Excel file path)
        |
   Read Excel File  ->  Extract Excel Rows
        |
   Pick Next Post  (first row with Status = "Scheduled")
        |
   Post to LinkedIn
        |
   Update Rows (Status = "Posted", Posted At = timestamp)
        |
   Convert to Excel  ->  Save Excel File
