# OSINT-handbook

## What is OSINT?

**Open Source Intelligence (OSINT)** is the process of collecting, verifying, analyzing, and correlating information from publicly available sources to produce meaningful intelligence.

OSINT can involve information gathered from sources such as:

* Search engines and public websites
* Social media platforms
* Public records and government databases
* News articles and online publications
* Publicly available documents and reports
* Domain, DNS, and certificate information
* Maps and geospatial sources
* Public code repositories
* Internet archives

The key difference between simply searching the internet and performing OSINT is **the methodology**. OSINT involves collecting relevant information, validating its reliability, connecting individual findings, and drawing conclusions from the available evidence.

> **OSINT does not mean accessing private accounts, bypassing authentication, exploiting systems, or obtaining information through unauthorized access.**

# 1. Search Engine Intelligence & Dorking
Mastering search engines unlocks vast information through precise techniques. Use these resources to master advanced searching:
* Google Advanced Search: https://www.exploit-db.com/google-hacking-database
* Bing Search Guide: https://www.bruceclay.com/blog/bing-google-advancedsearch-%20operators/
* DuckDuckGo Search Guide: https://duckduckgo.com/duckduckgo-help-pages/duckduckgo-helppages/%20results/syntax
* Alternative Engines: Specialized databases like "Yandex" and "Baidu" are essential for cross-border investigations and finding data outside the Western index.

# 2. Image Osint Tools (IMINT)
###  **Reverse Image & AI Search**
These tools help you find where an image has appeared online or identify the subject within it:
  * Google Image Search: https://images.google.com/
  * Yandex: https://yandex.com/
  * TinEye: https://tineye.com/
  * Lenso.ai: https://lenso.ai/en
  * PicDetective: https://picdetective.com/
  * Face Comparison: https://facecomparison.toolpie.com/
  * CrowdCounter: https://digitaldigging.org/crowdchecker/

###  **Metadata & Forensics (EXIF)**
Behind every digital image is hidden data that can reveal the “when” and “how” of a capture:
  * OnlineExifViewer: https://onlineexifviewer.com/
  * FotoForensics: https://fotoforensics.com/
  * 29a.ch Forensics: https://29a.ch/photo-forensics/#forensic-magnifier
  * AperiSolve: https://www.aperisolve.com/

# 3. Email OSINT
An email address can be a valuable starting point in an OSINT investigation. It can help connect publicly available information such as social media accounts, professional profiles, usernames, and other online references. By carefully correlating information from different sources, an investigator can use a single email address as a starting point to build a broader picture of the subject while verifying each finding before drawing conclusions.

###  **Professional Email Discovery & Extraction**
  * Hunter.io: https://hunter.io/
  * Phonebook.cz: http://phonebook.cz/
  * VoilaNorbert: https://www.voilanorbert.com/
  * SignalHire: https://www.signalhire.com/
  * ContactOut: https://contactout.com/
  * RocketReach: https://rocketreach.co/
  * GetProspect: https://getprospect.com/
  * Clearbit Connect: https://clearbit.com/

###  **Technical Verification & Validation**
Before acting on a lead, use these tools to ensure an email is active and valid:
  * Email Hippo: https://tools.emailhippo.com/
  * Verifalia: https://verifalia.com/validate-email
  * Mailmeteor: https://mailmeteor.com/tools/reverse-email-lookup
  * Experte Validator: https://www.experte.com/email-verification
  * IPQualityScore: https://www.ipqualityscore.com/reverse-email-lookup

###  **Email-to-Account Pivoting (Advanced Recon)**
These resources allow you to see where an email address is registered across the web:
  * Epieos: https://epieos.com/
  * Intelbase: https://intelbase.is/
  * Holehe: https://github.com/megadose/holehe
  * Mailcat: A GitHub-based utility that finds existing email addresses by nickname using API and SMTP checking methods.
  * Gmail Osint (Ghunt): https://gmail-osint.activetk.jp/
  * OSINT.Rocks / Gmail-OSINT: https://osint.rocks/
  * GitHub Email Finder: https://github-email-finder.netlify.app/
  * IntelligenceX: https://intelx.io/
  * Whatsmyname / Email Leak: https://whatsmyname.me/emailleak

# 4. Username Osint
When an email address does not directly match a target’s known alias, you can pivot to the username associated with that address and search for where it appears across the web. Username-search tools can check multiple platforms and services, helping you identify publicly available accounts that may be connected to the same username. This can provide a broader view of a subject’s online presence while still requiring manual verification to confirm that the accounts belong to the same person.
  * WhatsMyName.app: https://whatsmyname.app/
  * WhatsMyName.me: https://whatsmyname.me/
  * Namechk: https://namechk.com/
  * NameCheckup: https://instantusername.com/
  * InstantUsername: https://instantusername.com/
  * Maigret: https://github.com/soxoj/maigret
  * Sherlock: https://github.com/sherlock-project/sherlock
  * Userrecon: https://github.com/abhinavender/UserRecon
  * OSINT.Rocks / Username: https://osint.rocks/

# 5. Leak Osint
Once an email address or username has been identified, the next step is to check whether it has appeared in any known data breaches or security incidents. Publicly available breach databases can help identify exposed information associated with an account, such as old passwords, usernames, or other contact details. This information can provide useful context during an OSINT investigation, but any findings should be handled responsibly and verified through reliable sources.

###  **Breach Search Engines & Databases**
  * Have I Been Pwned (HIBP): https://haveibeenpwned.com/
  * HIBP Passwords: https://haveibeenpwned.com/Passwords
  * DeHashed: https://dehashed.com/
  * IntelX (Intelligence X): https://intelx.io/
  * Snusbase: https://snusbase.com/
  * LeakCheck: https://leakcheck.io/
  * WeLeakInfo: https://weleakinfo.to/v2

###  **Specialized Breach Tools**
  * BreachDetective: https://breachdetective.com/dashboard
  * 9ghz: https://9ghz.com/
  * DataBreach.com: https://databreach.com/

###  **Paste & Text Archives**
  * Pastebin: https://pastebin.com/
  * Ghostbin: https://ghostbin.com/

# 6. Social Media Osint (SOCMINT)
Social media platforms can be a valuable source of publicly available information during an OSINT investigation. People often share details about their interests, work, connections, activities, and locations through their profiles and posts. By reviewing and correlating this information across different platforms, investigators can build a better understanding of a subject’s online presence and identify relevant leads for further research.

###  **Username & General Search Tools**
  * WhatsMyName.me: https://whatsmyname.me/
  * WhatsMyName.app: https://whatsmyname.app/
  * Lookup-ID.com: https://lookup-id.com/
  * Social Mention: https://socialmention.net/
  * Social-Searcher: https://www.social-searcher.com/

###  **Twitter (X) Analysis & Conversion**
  * Followerwonk: https://followerwonk.com/
  * Twitonomy: https://www.twitonomy.com/
  * Tinfoleak: https://tinfoleak.com/
  * TweetHunter: https://tweethunter.io/
  * PostelApp: https://www.postel.app/twitter-user-id-converter
  * Twiteridfinder: https://twiteridfinder.com/

###  **Platform-Specific SOCMINT**
  * Codeofaninja: https://www.codeofaninja.com/tools/
  * Instadp: https://www.instadp.com/
  * Imginn: https://imginn.com/
  * Snapchat Map: https://map.snapchat.com/
  * IntelX Facebook Tools: https://intelx.io/tools?tab=facebook
  * CommentPicker: https://commentpicker.com/
  * WebVetted: https://webvetted.com/detect/social/

# Advanced Technique: Source Code & Unique ID Search
When a username or profile handle changes, a platform’s internal identifiers can sometimes help in correlating the same account across different references. Depending on the platform, these identifiers may appear in publicly accessible page data, metadata, or structured information within the source code. Searching the page source can sometimes reveal values such as user IDs, profile IDs, or member IDs. However, modern platforms frequently change their page structure and may hide or dynamically generate this information, so these techniques should be treated as a secondary method rather than a guaranteed approach. Always verify that an identified ID actually belongs to the intended account before using it for further investigation.

*  **Facebook ID Search:** Look for the string "userID":" within the source code to find the account's permanent numerical identifier. Alternative: Use Lookup-ID.com
*  
*  **LinkedIn ID Search:** Use the string li:member: in the page source to identify the unique member ID associated with a profile. Alternative: Look at the “Contact Info” pop-up or use a tool like SignalHire to extract the profile’s background ID.
*  
*  **Twitter ID Search:** Search for profile_banner: or related metadata tags in the source to locate the static Twitter user ID. Alternative: Use TweeterID or TweetBeaver to convert the handle instantly.
*  
*  **Instagram ID Search:** Identify the permanent account number by searching the source code for the profile_id: string. Alternative: Search the source for "user_id":" or "owner": {"id":". You can also use Instadp to view the profile data.
*  
*  **Pinterest ID Search:** Look for specific data-attribute strings or JSON blobs within the source to uncover the unique user identifier. Searching the source for "userId":" or "owner":{"id":" remains the most reliable way to find the permanent ID.
*  
These techniques are still worth trying, but you should treat them as a “Plan B.”

# 7. People Osint
Publicly available information about a person can often reveal more than they might expect. By combining information from public records, social media, professional profiles, and other open sources, an investigator can build a broader picture of an individual’s digital footprint. In cybersecurity and OSINT, this information can help identify potential security risks, understand what personal information is exposed, and assess how publicly available details could potentially be used in social engineering or account-security scenarios.

###  **Automated Reconnaissance & Investigation Frameworks**
  * Maltego: https://www.maltego.com/
  * SpiderFoot: https://www.kali.org/tools/spiderfoot/

###  **Identity & Visual Correlation**
  * WhatsMyName.app: https://whatsmyname.app/
  * WhatsMyName.me: https://whatsmyname.me/
  * FaceComparison Toolpie: https://facecomparison.toolpie.com/

###  **People Search Engines & Public Records**
  * Whitepages: https://www.whitepages.com/
  * Webmii: https://webmii.com/
  * 411.com: https://www.411.com/
  * Spokeo: https://www.spokeo.com/
  * X-Ray Contact: https://x-ray.contact/

# 8. Phone OSINT
A phone number can be a useful starting point in an OSINT investigation because it is often associated with multiple online services and accounts. Depending on what information is publicly available, a phone number may help connect an identity with social media profiles, messaging platforms, business listings, or other online references. By correlating these details carefully and verifying them through reliable sources, an investigator can build a broader picture of a subject’s digital footprint.

###  **Global Identification & Caller ID**
  * Truecaller: https://www.truecaller.com/
  * Sync.me: https://sync.me/
  * Infobel: http://infobel.com/

###  **Technical Reconnaissance & Scanning**
  * PhoneInfoga: https://github.com/sundowndev/phoneinfoga
  * PhoneIntel: https://github.com/phoneintel/phoneintel
  * OSINT.Rocks: https://osint.rocks/

###  **Pivoting & Breach Correlation**
  * WhatsApp.Checkleaked: https://whatsapp.checkleaked.cc/
  * Epieos: https://epieos.com/
  * X-Ray Contact: https://x-ray.contact/
  * DataBreach.com (Phone): https://databreach.com/Phone
  * LeakCheck.io: https://leakcheck.io/

# 9. Wireless OSINT Tools
Wireless OSINT involves collecting publicly available information about wireless networks, Bluetooth devices, cellular infrastructure, and other connected technologies without directly connecting to or accessing the devices. By using public databases, mapping services, and internet-wide search platforms, researchers can identify information such as network locations, device details, and exposed infrastructure. This can help build an understanding of the wireless and IoT footprint associated with a particular area or organization.

###  **Wireless Geographic Mapping**
  * WiGLE (Wireless Geographic Logging Engine): https://wigle.net/  The industry standard for wireless reconnaissance. This massive crowdsourced database maps hundreds of millions of Wi-Fi networks and cell towers globally. Search by SSID or MAC address to pinpoint exactly where a network is located.

###  **Internet-Wide Infrastructure Scanners**
While these tools do not directly scan local wireless signals, they can provide valuable information about devices and services that are publicly exposed on the internet. This can include routers, IoT devices, cameras, and other connected hardware, helping researchers understand what types of infrastructure are associated with a particular network or organization.

  * Shodan: https://www.shodan.io/
  * Censys: https://censys.com/

# 10. Website Osint Tools
Website OSINT is an important part of understanding an organization’s digital footprint. It involves gathering publicly available information about websites, domains, subdomains, technologies, and other online assets associated with an organization. By analyzing this information, researchers can identify the technologies in use, discover related infrastructure, and find publicly available contact or administrative information that may be useful for further security assessment.

###  **Domain & Infrastructure Analysis**
  * ViewDNS.info: https://viewdns.info/
  * MxToolbox: http://mxtoolbox.com/
  * BuiltWith: https://builtwith.com/
  * VirusTotal: https://www.virustotal.com/
  * VisualPing: https://visualping.io/
  * DNSlytics: https://dnslytics.com/reverse-ip
  * CentralOps: https://centralops.net/co

###  **WHOIS & Ownership Research**
  * Whois.com: https://www.whois.com/
  * WHO.is: https://who.is/
  * GoDaddy WHOIS: https://www.godaddy.com/whois
  * DNSimple WHOIS: https://dnsimple.com/whois

###  **Subdomain Discovery & Scraping**
  * Pentest-Tools Subdomain Finder: https://pentest-tools.com/information-gathering/find-subdomains-of-domain
  * OSINT.sh Subdomain: https://osint.sh/subdomain/
  * DNSDumpster: https://dnsdumpster.com/
  * TheHarvester: A powerful Python tool (pre-installed on Kali Linux) used to gather emails, subdomains, hosts, and employee names from public sources like Google and LinkedIn.
  * WebScraper.io: https://webscraper.io/

###  **Technical Intelligence & Archives**
  * Shodan: https://shodan.io/
  * Wayback Machine: https://web.archive.org/
  * WhatIsMyIPAddress: https://whatismyipaddress.com/
  * WhatsMyIP.com: https://whatsmyip.com/
  * SpiderFoot: https://www.kali.org/tools/spiderfoot/
  * Censys.io: https://censys.io/
  * nslookup: A fundamental command-line utility used to query DNS servers and find IP addresses associated with a domain name.

# 11.  Business OSINT Tools
Business OSINT involves gathering publicly available information about companies, their structure, ownership, key stakeholders, and business relationships. It can be useful for understanding an organization’s corporate and legal structure, researching its history, and performing due diligence. Public sources such as government filings, regulatory records, corporate registries, company websites, and financial reports can help researchers build a clearer picture of how an organization operates and who is connected to it.

###  **Corporate Registries & Legal Data**
  * OpenCorporates: https://opencorporates.com/
  * EDGAR (SEC): https://www.sec.gov/edgar/searchedgar/companysearch
  * Owler: https://www.owler.com/

###  **Pivoting to Professional Intelligence**
  * Glassdoor: https://www.glassdoor.com/
  * LinkedIn Company Pages: https://www.linkedin.com/

# 12. Geospatial Intelligence (GEOINT)
Geospatial Intelligence (GEOINT) focuses on understanding the where and when behind an investigation by analyzing geographic information and visual data. It can involve satellite imagery, maps, aerial photographs, terrain data, and street-level imagery to identify locations and understand changes over time. By comparing visual clues such as buildings, roads, landscapes, and landmarks with available geographic data, researchers can estimate or verify a location and better understand the context surrounding an event.

###  **Mapping & Satellite Imagery**
  * Google Maps: https://www.google.com/maps
  * Google Earth: https://earth.google.com/
  * Zoom Earth: https://zoom.earth/maps/radar/
  * Wikimapia: https://wikimapia.org/
  * Snapchat Map: https://map.snapchat.com/

###  **Ground-Level & Tactical GEOINT**
  * Mapillary: https://www.mapillary.com/
  * GPS Visualizer: https://www.gpsvisualizer.com/
  * FindPicLocation: https://findpiclocation.com/
  * GeoImgr: https://tool.geoimgr.com/
  * PeakVisor: https://peakvisor.com/

# 13. Dark Web & Virtual Currency OSINT
Dark web and blockchain OSINT require specialized techniques because these environments often use anonymity, pseudonymous identities, and decentralized infrastructure. Investigators can use publicly available blockchain data to analyze transactions, trace the movement of funds, and identify connections between cryptocurrency addresses. Similarly, research into the dark web can help identify publicly accessible onion services and gather information about online communities or activities. By correlating these sources with other reliable information, investigators can build a clearer picture of entities and financial activity without assuming that a pseudonymous address directly represents a real-world identity.

###  **Safe Access & Dark Web Discovery**
  * Tor Project: https://www.torproject.org/
  * Brave Browser (Tor Mode): https://brave.com/
  * Ahmia Search Engine: https://ahmia.fi/
  * DuckDuckGo (Onion Version): https://duckduckgogg42xjoc72x3sja7o784uuy6aov発m67v.onion/

###  **Blockchain Analysis & Cryptocurrency OSINT**
  * Blockchain.com Explorer: https://www.blockchain.com/explorer
  * Bitcoin Who’s Who: https://bitcoinwhoswho.com/
  * Chainabuse (formerly BitcoinAbuse): https://www.chainabuse.com/

###  **Community & Forensic Intelligence**
  * Reddit (r/OSINT & r/DarkNet): https://www.reddit.com/r/OSINT/

# 14. Data Analysis & Decoding
  * CyberChef: https://gchq.github.io/CyberChef/
  * dCode.fr: https://www.dcode.fr/en


# Ethics & Professional Responsibility

With the ability to uncover deep information comes a heavy burden of responsibility. As investigators, we must maintain a strong moral compass:

* **Do No Harm:** Use OSINT for defense, verification, and justice — never for harassment, stalking, or malicious doxing.

* **Respect Privacy:** Just because information is “public” does not always mean its use is ethical; always consider the intent and impact of your research.

* **The Rule of Three:** Never consider a finding a fact until it has been cross-referenced and confirmed by at least three independent sources.


# Disclaimer

This toolkit is intended solely for educational purposes and ethical cybersecurity research. It should only be used in authorized investigations and responsible security research. The author does not support or encourage illegal activities, unauthorized access, harassment, or misuse of information. Always respect applicable laws, privacy regulations, and the Terms of Service of the platforms being researched. Users are responsible for how they use the information and resources provided in this toolkit.
