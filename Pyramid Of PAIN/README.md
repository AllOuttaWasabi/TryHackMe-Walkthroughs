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


### Disclaimer - DO NOT PROCEED TO ANY IPs or WEBSITES MENTIONED IN THIS WALKTHROUGH.  MALICIOUS IPs ARE PRESENT.  These IPs have been included for WALKTHROUGH PURPOSES.  ANY DAMAGE THAT IS DONE THROUGH YOUR OWN ACTIONS IS ON YOU!  

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
