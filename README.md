# Drawing review

Free web page to review sheet-metal manufacturing files straight from a Google Drive folder:
STEP model in 3D (explode, one piece, measure), DXF flat patterns, PDF drawings, automatic pre-checks,
and Approve / Request changes sent by WhatsApp or email.

How to use: open the site, paste a Google Drive folder link (sharing: "Anyone with the link"),
add your WhatsApp number and/or email, and send the review link to the engineer.

Setup: put a Google Drive API key in `index.html` (`const API_KEY=`). The key only reads public files.
