# Web Server Lab

- Web server that handles one HTTP request at a time. WebServer.py accepts
  and parses the HTTP request, gets the requested file from the server’s file system, creates an HTTP response
  message consisting of the requested file preceded by header lines, and then sends the response directly to
  the client. If the requested file is not present in the server, the server sends an HTTP “404 Not
  Found” message back to the client.

----

# AUTHOR INFO

- Full Names: Karam Aboul-Hosn
- Student IDs: 2437165
- Chapman Emails: kaboulhosn@chapman.edu
- Course Number And Section: CPSC-353-04
- Course Name: Data Communication and Computer Networks
- Assignment Or Exercise Number: Lab 1: Web Server Lab

## ERRORS

- N/A

## RUN AND TEST SERVER

- Run **WebServer.py**: `python3 WebServer.py`
- Open the client browser.
- **Paste the URL**: http://<host-ip>/HelloWorld.html
- Replace <host-ip> with the IP address of the host that is running the server.

## SOURCES

- Content learned in this course and previous courses.
