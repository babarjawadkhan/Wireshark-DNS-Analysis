DNS Query Analysis
	•	Source IP: 172.20.10.2
	•	Destination IP :172.20.10.1
	•	Query Name: google.com
	•	Query Type: A
	•	Transaction ID: 0x84b1
	•	Protocol Used: UDP
	•	Port: 53

DNS Response Analysis
	•	Response IP: 172.20.10.1
	•	Response Code: No error (0x8180)
	•	Number of Answers: 6
	•	Time between request and response: 78.368000 milliseconds.
	•	Did the Transaction IDs match? Yes. 
	•	How long did the response take?  78 ms.
	•	Was recursion enabled? Yes.
	•	Was it IPv4 (A record) or IPv6 (AAAA)? A record.
	•	Was it using UDP or TCP? UDP.    
Notes : 
Security Analysis
	•	DNS uses UDP which does not provide built-in reliability.
	•	This makes DNS vulnerable to spoofing and amplification attacks.
	•	Monitoring DNS traffic is critical for detecting tunneling and malware beaconing
activity.
Indicators Checked
	•	Repeated DNS queries.
	•	Long/random subdomains.
	•	NXDOMAIN responses.
	•	Large DNS response size




