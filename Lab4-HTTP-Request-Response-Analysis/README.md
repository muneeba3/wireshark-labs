# Lab 4 – HTTP Request/Response Analysis

##  Objective
Capture and analyze HTTP requests and responses to understand web communication and headers.

## 🛠 Tools
- Wireshark
- Browser (Chrome/Firefox)


##  Steps
1. Started Wireshark capture.
2. Opened http://google.com in browser.
3. Clicked http://testphp.vulnweb.com/signup.php and submitted forms.
4. Applied filter: `http`.

##  Findings
- **GET Request** → Browser requested homepage and resources.
- **HTTP Response** → Server returned 200 OK with headers and content.
- **POST Request** → Submitted form data.
- **HTTP Response** → Server responded with 302 Redirect.
- **Cookies / Headers** → Session cookies and User-Agent observed.



##  Files
- `http-capture-example.pcapng`
- `screenshot4.png`
- `README.md`
