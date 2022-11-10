## Pyramid OF PAIN

Used to improve the effectiveness of Cyber Threat Intelligence

Levels (In Increasing Difficulty)

<ol>
  <li>Hash Values (Trivial)</li>
  <li>IP Addresses (Easy)</li>
  <li>Domain Names (Simple)</li>
  <li>Network/Host Artifacts (Annoying)</li>
  <li>Tools (Challenging)</li>
  <li>TTPs (Tough)</li>
</ol>


### Disclaimer - DO NOT PROCEED TO ANY IPs or WEBSITES MENTIONED IN THIS WALKTHROUGH UNLESS SPECIFIED FOR LEGITIMACY.  MALICIOUS IPs ARE PRESENT.  These IPs have been included for WALKTHROUGH PURPOSES.  ANY DAMAGE THAT IS DONE THROUGH YOUR OWN ACTIONS IS ON YOU!  

### Hash Values

<ol>
  <li>Provide the ransomware name for the hash '63625702e63e333f235b5025078cea1545f29b1ad42b1e46031911321779b6be' using open-source lookup tools...
  </li>
  
  >Go to virustotal.com and click the search option.  Paste the hash into virustotal. Go to community after it loads.  You can see where this indicator has been linked to the __Conti__ ransomware.
</ol>




### IP Addresses

<ol>
  <li>What is the ASN for the third IP address observed?</li>
  
  >Open the app.any.run link.  Click on the connections tab.  Scroll over to the ASN tab.  You should see the name, __Host Europe Gmbh__
  
  <li>What is the domain name associated with the first IP address observed?</li>
  
  >Look at the Domain column.  The first entry should be __craftingalegacy.com__
</ol>



### Domain Names

__Click the link to the app.any.run report to answer the first question.__

<ol>
  <li>Go to this report on app.any.run and provide the first malicious URL request you are seeing, you will be using this report to answer the remaining questions of this task.</li>
  
  >Open the link.  Go to the connections tab.  Look at the Domain column for the first row.  You should see __craftingalegacy.com__ 
  
  <li>What term refers to an address used to access websites?</li>
  
  >How do you map an IP address to text?  You do so by using a __Domain Name__.
  
  <li>What type of attack uses Unicode characters in the domain name to imitate the a known domain?</li>
  
  >"Punycode is a system for converting words that can't be written in ASCII"
  
  >"Unicode Domains"
  
  >When a victim is forced to click a link that otherwise looks authentic, it's called a __Punycode Attack__.  Look up in that section for more information.
  
  <li>Provide the redirected website for the shortened URL using a preview: https://tinyurl.com/bw7t8p4u - (Checked for legitimacy)</li>
  
  >Simply add a + on to the end of the tinyurl and press enter.  Look down.  You'll see the redirected website which is, __https://tryhackme.com/__   (Not a paid sponsor.)
  
</ol>

### Host Artifacts

<ol>

<li>What is the suspicious IP the victim machine tried to connect to in the screenshot above?</li>

>Look at the second image.  Look at the TCP receive.  It appears that there's outbound communication to an IP address.  This could be an issue.  Open up virustotal.com in a browser and search the ip 35[.]214[.]215[.]33 (remove the brackets. IT DOES NOT APPEAR MALICIOUS BUT IT IS.  __WARNING: This IS a malicious IP so do not enter directly into your browser.__  It WILL connect to it and you WILL be at risk.)


<li>Use the tools introduced in task 2 and provide the name of the malware associated with the IP address</li>

> Look at the virustotal page you have pulled up from the previous question. You can see the name of the malware if you go to relations or community.  
  
>It's __Emotet__.  
__Emotet used Hyper Beam__


<li>Using your OSINT skills, what is the name of the malicious document associated with the dropped binary?</li>

>Look at the pictures.  Should be self-explanatory.  It's __G_jugk.exe__

<li>Use your OSINT skills and provide the name of the malicious document associated with the dropped binary</li>

>Google the file name.  Avoid searching just for the file.  Search for it by using terms such as, "What is __insert file name__".  You will see a couple of sandbox environments pop up.  Click on the any.run sandbox and look for the name.  It should stick out.

>It's __CMO-100120 CDW-102220.doc__

</ol>


### Network Artifacts

<ol>
  <li>What browser uses the User-Agent string shown in the screenshot above?</li>
  
  >Copy and paste the hint into a search engine and see what browser it is.
  
  >It's __Internet Explorer__ !  
  
  <li>How many POST requests are in the screenshot from the pcap file?</li>
  
  >Look at the first image in the section.  How many post requests do you see?  It should be __6__.
</ol>


### Tools

<ol>
  <li>Provide the method used to determine similarity between the files</li>
  
  > __Fuzzy Hashing__ is a way to check similarity between files.
  
  <li>Provide the alternative name for fuzzy hashes without the abbreviation </li>
  
  > Go to the SSDeep site.  You should see the name at the top of the documentation.  It's __context triggered piecewise hashes__ 
</ol>

### TTPs

<ol>
  <li>Navigate to ATT&CK Matrix webpage. How many techniques fall under the Exfiltration category?</li>
  
  >Pull up MITRE ATT&CK matrix.  Look at the EXFILTRATION section.  How many are there?  There should be __9__.
  
  <li>Chimera is a China-based hacking group that has been active since 2018. What is the name of the commercial, remote access tool they use for C2 beacons and data exfiltration?</li>
  
  >Building on the last question.  Do you see something in exfiltration relating to C2?  Click that link.  Now look down under procedure examples.  You should see some IDs, APT names and descriptions.  Look for __Chimera__ and see what it says.
  
  >They use __Cobalt Strike__
</ol>
 
