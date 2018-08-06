## Building a Website Day 17
### Hosting and deployment demo

+ log in to 1&1
+ open cyberduck

--

+ on the 1&1 dashboad, choose secure FTP account
	+ in the hosting tile or in the side bar
+ everyone should have a default user
+ change the password to something you'll remember
+ note the information here
	+ server/host link
	+ SFTP is the protocol
	+ the port number

--

+ in cyberduck, click new connection
+ from the dropdown, change the protocol to SFTP
+ paste the server address from 1&1 page
+ make sure the port number is correct
+ type your user name (you can copy paste)
+ type your password
	+ use "show password" or you may type it wrong
+ if you are on a lab computer UNCHECK the keychain box
	+ otherwise any doofus who opens cyberduck has access to your webspace!!
+ if you get an error one of these three things are highly likely: 
	+ you copy and pasted something wrong
	+ your password hasn't updated yet (give it 5 minutes)
	+ you typed the wrong password in 1&1, try resetting it, then wait 5 minuts for it to upload

--

+ in cyberduck, drag a folder into the web space
	+ your musician website, or another website we've made it in glass
+ make sure it has a good name
	+ NO SPACES, NO SPECIAL CHARACTERS
	+ servers are VERY DUMB
+ make sure the folder has an index.html

--

+ back in 1and1
+ manage domains
+ click on your domain
+ destination should say "webspace"
+ click on target
+ give it a second to load the folders
+ choose the folder you just dragged into cyberduck
+ your website should update in the next few minutes and work!!

--

+ that's how you point your main page, you can also do it with subdomains
+ create a new subdomain
+ point it to the folder
+ redirect your main webspace somewhere else

--

### Email

+ since you own webspace, you can have an email address
+ on the 1&1 dashboard, choose "email and office"
+ on the right, create a 1and1 basic mail account
+ enter your information
+ Recommend not checking virus/spam protection, since you don't want to miss emails from strangers
+ click save
+ you can access your email box at: https://webmail.1and1.com