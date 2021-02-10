# redirect-validator
Input a file with 2 columns in which the first column is the origin of a redirect and the second column is the proposed destination. 

From there you'll be prompted with a series of questions to help provision for your list with or without hostnames (you can enter it if your list is page paths only)

You're also given the opportunity to swap a Production URL out for a Test/Staging URL. 

Export options include:

  • If you use Google Sheets as the input, your export will hit your desktop
  
  • If you install this on your machine and use a filepath as your input, your export will hit the folder in which the source file lives

The output is your list, with any problematic redirects sorted up to the top. 

  • "Problematic" being defined as any redirect that has a destination URL with a non-200 status code OR the actual and proposed destinations do not match
