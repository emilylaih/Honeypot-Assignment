# Honeypot Assignment

**Time spent:** **X** hours spent in total

**Objective:** Create a honeynet using MHN-Admin. Present your findings as if you were requested to give a brief report of the current state of Internet security. Assume that your audience is a current employer who is questioning why the company should allocate anymore resources to the IT security team.

### MHN-Admin Deployment (Required)

**Summary:** How did you deploy it? Did you use GCP, AWS, Azure, Vagrant, VirtualBox, etc.?
I use Google Cloud Platform to deploy it.

<img src="GCD.png" width="700" height="300"> 

### Dionaea Honeypot Deployment (Required)

**Summary:** Briefly in your own words, what does dionaea do?
Dionaea return the ports that has been scanned. For instance in my case, I nmap scan my Dionaea honeypot to test it and my mhn-admin site shows the ports that nmap have scanned as attacks.  

<img src="attacks.gif">

### Database Backup (Required) 

**Summary:**
 What is the RDBMS that MHN-Admin uses? MHN-Admin uses MongoDB.

 What information does the exported JSON file record?
 

*Be sure to upload session.json directly to this GitHub repo/branch in order to get full credit.*

### Deploying Additional Honeypot(s) (Optional)

#### X Honeypot

**Summary:** What does this honeypot simulate and do for a security researcher?

<img src="x-honeypot.gif">

### Malware Capture and Identification (Optional)

#### X Malware

**Summary:** How did you find it? I go to payloads and select dionaea.capture in the mhn-admin site. Which honeypot captured it? 
I use Honeypot Dionaea to capture it.

What does each malware do?

MD5 Hash: 6df195b040f1b3af16df03753674cf97
 *Run `md5sum` on the file and record the hash here.*

SHA512 Hash: 9c8c827981a815f9c8e51a97505765df083b88c140eaaf77132644bad6d900557af3c49190791f7542dc27dff4e676f3d295f9c48ddcbfa6d2741d1c28449160
*Run `sha1sum` on the file and record the hash here.*

<img src="malware.gif">

## Notes

Describe any challenges encountered while doing the assignment.
