# Streampalv2
- Free Streaming Search Engine Website called StreamPal which doesnt host any files directly on its site.
- With a P2P Video Providing Service Included ontop of the search engine design!
- We hope to make a more secure method of p2p streaming using ipfs gateway system along with a custom event source server to allow secure communication channel to browser clients and file providers without the need for ip address communications by using a custom event source server we can have all the communications proxied through it to reduce ip address of browser clients from being sent to file providers and by using ipfs and not direct urls we hope to cut down on alot of the frame injection exploits that would have been possible if we had not used the ipfs and require either ipfs CID v1.0 or the ipns CID locations instead of urls so urls are generated from the browser side to cut down on these potential exploits. again had we not done a system like this!
- We also have a niffty file Provider tool Application programmed in nodeJS and using the Electron Module for graphical display to allow drag and drop of video files easily into the proper folder structures along with the easy auto upload to ipfs and publish function it has built into the application so it will help cut down on alot of clicks and drags and folder naming as it auto uploads all the Repositorys you create under it to the ipfs in there own individual folders and each with to there own ipns location so you can compartmentalize where files are to reduce space requirements for some public node access to host it! and decreases the response time it takes for the file to be available publicly by using the multi repository setup inside our application also generating a repository is as simple as filling out a text input box and pressing a button then selecting that repository from a dropdown so you will be actively working on that repository.
- This File provider tool we are hoping to publicly release within the next month got a month of final testing and debugging any finale bugs before public release -3/23/2023 est time of release will be 4/23/23.

# Current Features
- Functioning Progressive Web App
- Watch History
- Bookmarks
- Show all
- Scroll layout like netflix to help reduce the need for multiple pages
- All designed within a single html file not constantly loading a new site for each Tv show or Movies all contained within one Site which is StreamPal
- Sandboxed Embedded Video Players
- Non Sandboxed Embedded Video Players
- Spiders and Scrapes Using public apis to gather additional video player server providers!
- Tv Section is complete! besides the genre section
- Search Bar is fully functionable and Complete! so you can search any movie that is in the TMDB.
- Server Selector on the watch page along with episode and season selector for tv shows!
- Movie Section is complete! beside the genre sections

# Coming Soon Features
- Watch Later List aka Watch List incase you dont want to bookmark but might want to peep somethings out without cluttering your bookmarks!
- Tv Genre Section
- Movie Genre Section
- And maybe a few other things also we include a Documentation page for anyone who wants to become a file provider without having to have a server using IPFS network but this service isnt complete
- Once the Tools are completed like a script to help auto add to ipfs file folders and publish for you etc.. along with The File Structure Generator Tool which will help generate the Folder structures properly
- Along with including URL list editor tool to help with providing URLS for the sources and eventually i imagine someone will take this strucuture design and automate the upload of files and storing of urls to be a URL provider

#   Updates
# 3/11/23
- Currently have a working Electron Node JS Application for File providers to be able to provide through smee just finishing on touching it up and making it easier to use with some drag and drop functions before releasing along with some configuration options which is going to require me to redo some of it quite a bit of its coding actually so it will be coming out soon Also Another Project will be working on is the Cache Database Provider incase there node is not receiving smee msgs but they where cached by database provider the database provider will ensure the file providers files will be accessible! basically this just listens in on them keeps a db of there ping.json Structure each provider you have that can provide a file you post a array list of them to the smee ensuring the system stays running! probably gonna have to include file size checks to ensure files wont go over something like 120mbs or something like this!
- if you want to peep the nodeJS application you can at the replit link here https://replit.com/@JohnsFriends/StreamPal-Browser-Tool-In-NodeJS?v=1 havent pushed the electron update to the replit yet but will soon once i finish up the final touches!

# Our Goals
- We wish to decentralize video streaming of movies and tv shows along with making it as mobile friendly as netflix or plutotv or tubi but instead of using a app you can do it straight through the browser
- We hope to be able to cut down loads of ads by sandboxing the embedded video players but sadly some servers detect sandbox so for those servers we recommend using the Brave browser
- We hope you enjoy our site and as always we wish to remain as legal as possible which is why we don't directly host any content which is listed on our website and neither are we affiliated with the providers in anyway so we are not held liable for any content that may break any copyright infringments.


# Disclaimer
- All Files and Content/Videos/Pictures displayed on the site is not directly hosted by or associated with StreamPal in any means or anyway so please be sure to reach out to each Individual File Providers server if you have any issues with a File or Content/Video/Picture that they may have posted!
- This site is nothing more then a search engine as such just like any other search engines out there!
- StreamPal and I the sole creator of it am not legally liable for any copyrighted materials or content that it may find and display on the site so therefore StreamPal or Github is NOT responsible for any of the material displayed on the https://john1234brown.github.io/streampalv2 Website!
- If you have any issues with material that may be displayed please find out what server the content is displayed on and properly serve proper DMCA notices to those servers we do not host any files on any of our servers or Github's servers as that would be breaking TOS agreement with Github!
- We do not and will not create any kind of censorship on our site or our search engine if there is a file available from a server it will display it if you have issues again please reach out to those servers we do not Condone or Advise the publishing of Copyrighted Material!
- Although we advise how to publish and where to publish we trust the users will properly post legal content that does not infringe on any Copyrights!
