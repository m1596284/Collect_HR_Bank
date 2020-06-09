# Collect_HR_Bank
Collect information from the website of human resources bank

1. Change key word to your target position.
2. Run the py and it will start:
   1. Counting how many available jobs and their company in current page.
   2.Send "GET" request for each page of job then parsing the infromation.
    1. Download the woff file and convert it to xml format.
    2. Indexing each unicode in xml table.
    3. Identify the signature of each encoding word.
    4. Use code table to decode those word to get mail and phone.
   3. Send "GET" request for each page of company then parsing the infromation.
    1. Download the picture of phone number.
    2. Converting and processing all pixel data into numeric.
    3. Indexing the edge of ecah number.
    4. Use code table to decode those word to get phone number.
   4. Output data to txt file.
