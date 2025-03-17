# parameter-tampering
Introduction
Parameter tampering is a type of security attack where parameters exchanged between a client (such as a web browser) and a server are altered by an attacker to gain unauthorized access to data or to exploit vulnerabilities. These parameters are typically part of HTTP requests, such as query strings, form fields, cookies, or HTTP headers.
The goal of parameter tampering can vary depending on the attacker's
Data Manipulation: Attackers may modify parameters to change data being sent to the server or received by the client. For example, altering the price of a product in an online shopping cart by modifying the corresponding parameter in the request. 
Privilege Escalation: By modifying parameters related to user authentication or authorization, attackers can attempt to escalate their privileges. For instance, changing a user's role from regular user to administrator by manipulating parameters in an HTTP request.
