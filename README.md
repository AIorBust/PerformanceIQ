# PerformanceIQ
Functions and code for Performance IQ

Function 1 - will create the JSON contract bundle by pulling data from Power BI / SQL and writing the JSON file to the data lake.

Function 2 - will:
1.retrieve the following files from the data lake (JSON contract, system prompt, user prompt)
2. pass the JSON, system prompt and user prompt to Open AI 4o LLM to generate the weekly insights report in markdown
3. write the markdown file to the data lake
4. send email to notify it's ready 

** maybe the function to read and write files to/from the data lake should be generic. We may need to call them often