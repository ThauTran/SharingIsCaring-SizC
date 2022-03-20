- Source: https://www.youtube.com/watch?v=qwA6MmbeGNo&t=90s&ab_channel=TheCyberMentor
- Title: Open-Source Intelligence (OSINT) in 5 Hours - Full Course - Learn OSINT!
For Educational Purposes ONLY	:nerd_face:	:nerd_face:
---
## `whatisit`
---
## `whatisinsidethisfile`
1. What is OSINT?                                     
2. Sock Puppets                                       
3. Creating Sock puppet Account                      
4. Search Engine Operator                             
5. Viewing EXIF Data (Exchangeable Data              
6. Reverse Image Searching                           
7. Physical Location OSINT                           
8. Identify Geographical Locations                   
9. Creepiest OSINT Tool                               
10. Discovering Email Addres                          
11. Password OSINT                                    
11.A. Huting Breached Credentials            
12. Hunting Usernames and Accounts
13. Searching for People*
14. Voter Records
15. Hunting Phone Numbers
16. Discovering Birthdates
17. Seraching for Resumes
---
# **1. What is OSINT?**
  - Open-source intelligence
  - A multi-methods methodology for :
    + Collecing, analyzing, and making decisions about data accessible in publicly available sources
    + Data, info about people, organization
  - Intelligence lifecyle:
    + Planning & Direction -> Collection
      * Look for Who, What, When, Where, and How, then make a plan
    + Collection -> Processing & Exploitation
      * How do we gather information we need for the attacking
    + Processing & Exploitation -> Analysis & Production
      * Use the collected data to put on act
    + Analysis & Production -> Dissemination & Integration
      * Process the collected data, and put all info in the document (plan)
    + Dissemination & Integration -> Go back to Planning & Direction
      * Present all collected info. and completed documents to client
    + This life cycle is always on GOING
  - Tools:
    + GhostRecon: https://github.com/DR34M-M4K3R/GhostRecon
---    
# **2. Sock Puppets**
  - FAKE account, fake person, fake identity BUT "REAL"
  - Purpose: To not draw attention to ourselves
  - This Sock Puppets account is NEVER used in your IP, or anything that relates to us
  - Main goal: To investigate others without getting investigation back to ourselves
---
# **3. Creating SOCK PUPPETS**
  - Never use our personal device to used the sock puppet account.
    + Sources:
      * jackcreps.com       : (Page not found - Try it again in the future)
      * secjuice.com        : https://www.secjuice.com/the-art-of-the-sock-osint-humint/
      * reddit.com          : https://www.reddit.com/r/OSINT/comments/dp70jr/my_process_for_setting_up_anonymous_sockpuppet/
      * fakenamegenator.com : Creating a fake info. FEMALE is recommended :)
      * thispersondoesnotexist.com : Profile picure. AI generator
      * privacy.com         : Virual debit card. It does not tight to your name or any of your information
      * A BURN PHONE        : Mint card recommended
  - :skull_and_crossbones: ***IP Address :skull_and_crossbones: : MAKE SURE, NOT USE YOUR PERSONAL LAPTOP (Home Network) to creat a SOCK PUPPET***
  - :grin: Personal experience :grin:: Find the picture of the person with a lot of make-up on. It's very hard to do a reverse search image on the person :wink:  
---      
# **4. Search Engine Operators**
  - google.com
    + password `site:` testla.com `filetypE:`xlsx
    + websitename `intext:`password `site:`specificsite.com (intext is most common used)
    + websitename `inurl/intitle/intext:`specifictest password `site:`specificsite.com
    + Look for **SUBDOMAIN**:
      * `site:`testla.com `-www` `-forums` (eliminate the www and forums site)
    + Advanced Search: https://www.google.com/advanced_search
  - More: Yandex, Duck,...
--- 
# **5. Reverse Image Searching**
  - images.google.com (best source) : 10/10
    + Drag and drop the image in the search bar
  - yandex.com/images/              : 8/10 - https://yandex.com/images/
  - tineye.com                      : 6/10 - https://tineye.com/
  - Note: Female with MAKE UP is the best source :stuck_out_tongue_winking_eye::stuck_out_tongue_winking_eye:
---
# **6. Viewing EXIF Data (Exchangeable Data)**
  - Nowadays, a lot of companies protect their user's info, but there are still possible for us to grab infor from a taken image/picture
  - exif.regex.info/exif.cgi
    + This site will analyze the uploaded image, and provide a lot of information abou the image
-------------------------------------------------------    
# **7. Physical Location OSINT**
  - Physical Penetrastion test
  - Looking at the satellie images, or using a drone flyting around to gather useful information
  -  Goals:
    + How to get access to the specific place - physical osint
    + Determine if the physical security is good enough: smoking area, trash door, etc.
-------------------------------------------------------    
# **8. Identify Geographical Locations**
  - geoguessr.com (fun game to play around, improve finding skill)
  - site: https://somerandomstuff1.wordpress.com/2019/02/08/geoguessr-the-top-tips-tricks-and-techniques/  
-------------------------------------------------------  
# **9. Creepiest OSINT Tool**
  - Source          : https://www.youtube.com/watch?v=uBynB50liTw&ab_channel=TheCyberMentor
  - Site            : Pimeyes.com (Be careful!)
-------------------------------------------------------  
# **10. Discovering Email Address**
  - hunter.io       : Find the pattern of a specific company - https://hunter.io/
  - phonebook.cz    : Domains, URLs, Email addresses (Good resource) - https://phonebook.cz/
  - voilanorbert.com: https://www.voilanorbert.com/
  - clearbit Connect: Google Chrome only (Good resource), it contains all company with email of employees        
  - tools.verifyemailaddress.io : Verify the email is valid. Try to catch "This email does not exsits" - https://tools.emailhippo.com/
  - email-checker.net/validate  : Verify the validation of an email
  - :smiling_imp::smiling_imp::smiling_imp: ***DO NOT UNDERESTIMATE `"FORGOT PASSWORD?"` section***:smiling_imp::smiling_imp::smiling_imp:
-------------------------------------------------------
**11. Password OSINT**
  - Identify password's pattern
-------------------------------------------------------  
# **11.A. Huting Breached Credentials** 
  - dehashed.com (cost money : $4.49/week) - adobe database
    + Ability to search by a lot of options: Email, Username, IP, Name, Address, Phone, VIN
  - hashes.org        : http://dan.hasher.org/
  - Weleakinfo.to     : The old wevbsite was shut down, but not it has the new site - https://weleakinfo.to/
  - leakcheck.io      : 9/10 - https://leakcheck.io/
  - snusbase.com      : https://snusbase.com/
  - scylla.ao         : 9/10 : using different pattern, format to find info. about email or any leaks. CURRENTLY DOWN - https://scylla.so/
  - haveibeenpwned.com: 10/10 (most updated database) - https://haveibeenpwned.com/

# **12. Hunting Usernames and Accounts**
  - namechk.com       : Find AVAILABLE username/domain - https://namechk.com/
  - whatsmyname.app   : Checking username - https://whatsmyname.app/
  - namecheckup.com   : checking available username to see where it appears on the internet - https://namecheckup.com/

# **13. Searching for People**
  - whitepages.com       : 9/10 - https://www.whitepages.com/
  - truepeoplesearch.com : 10/10 - https://www.truepeoplesearch.com/
  - webmii.com           : 8/10 - https://webmii.com/
  - thatsthem.com        : research for IP address, address - https://thatsthem.com/
  - 411.com/ spokepo/com/ GOOGLE.com

# **14. Voter Records**
  - ONLY use this with FULL PERMISSION. Good source to find information
  - voterrecords.com

# **15. Hunting Phone Numbers**
  - Try with Google first. We may be able to find the pattern or the area of the number is from
  - 665-112-1234 or "six-six-five one-one-two one-two-three-four"
  - Use icon/emoji when find the phone number since ppl usually "decorate" their phone number with a little icon
  - truecaller.com: https://www.truecaller.com/
  - calleridtest.com: https://calleridtest.com/ 
  - :smiling_imp::smiling_imp: AGAIN, Don't underestimate "FORGOT PASSWORD." The system will give the format of the phone number or email domain, or anything the "real users" used as a recovery method when they forget their password. :smiling_imp::smiling_imp:
  - inforbel.com : look up other country phone number pattern - https://www.infobel.com/fr/world
  
# **16. Discovering Birthdates**
  - Tools: 
    + Google: Using search engine to find info
      * Example: "Example Name" birthday or "Example Name" `intext:`"happy birthday" `site:`facebook.com 

# **17. Seraching for Resumes**
  - Find more information about someone's background: Companies, other personal information
    + Images is a good place to look for
    + Using search engine:
      * Example: "Example Name" resume `filetype:`pdf site:linkedin.com

# **18. Twitter OSINT**
  - [Ultimate searching guide](https://developer.twitter.com/en/docs/twitter-api/tweets/search/integrate/build-a-query) - Source: twitter
  - [Twitter Advanced Search](https://www.tweetbinder.com/blog/twitter-advanced-search/) - Source: tweetbinder
  - Using `geocode`by using the cordinate of the specific area (google map)
  - Other tools:
    + [Socialbearing](https://socialbearing.com/): (9/10) Statistics of all the activities of a specific account
    + [Twitonomy](https://www.twitonomy.com/): (9/10) Analyzing other people's file. Same as above
    + [Mentionapp](https://mentionmapp.com/): See the connection of the user. Who do the user talk to, and more
    + [Tweetbeaver](https://tweetbeaver.com/): Twitter ID lookup. Storing the ID in ase the user change his/her username
    + [Spoonbill](https://spoonbill.io/): (8/10) All info about a specific twitter account
    + [Tinfoleak](https://tinfoleak.com/): Also collecting data from a user
  - Another :sunglasses:COOL:sunglasses: tool: 
    + [Tweetdeck](https://tweetdeck.twitter.com/)
      * Adding columns, specifying what information we want to "monitor" in twitter: Geo cordinate, @Username, Date...

# **19. Facebook OSINT**
  - Using Searching function in Facebook is good enought for gathering information.
  - Other tool:
    + Intelx.io(#https://intelx.io/) - `View page source` by using RIGHT CLICK, then find USERID

# **20. Instagram OSINT**
  - [Codeofaninja](#https://codeofaninja.com/)
  - Utilize the image to do [REVERSE IMAGE SEARCH](#6-reverse-image-searching)
# **21. Snapchat OSINT**
  - Users usually enable their location
  - [Snapmap](#https://map.snapchat.com)
# **22. Reddit OSINT**
  - Searching bar
  - [Advanced Search](#https://www.makeuseof.com/tag/right-way-search-reddit/)
  - Using GOOGLE. Ex: "Example" site:reddit.com
# **23. Linkedln OSINT**
  - Utilize [Reverse Image Search] - Finding related post, images,...
# **24. Tiktok OSINT**
 - Utilize [Reverse Image Search] - Profile picture
