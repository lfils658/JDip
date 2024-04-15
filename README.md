# JDip
JDip is an online web portal for your needs.

## ABOUT
My uncle, John DiPlacido, made a web portal for our family. Originally called ".: John's Home Page :.", it had many web portal features: a news feed, chatroom, guestbook, etc. Unfortunately, Uncle Johnny passed a few years back. I decided to remake it in his name and titled it "The J" as a tribute to him. Here I am sharing some original snippets of the source code (retrieved from the Internet Archive, located in the [`old`](https://github.com/lfils658/JDip/tree/old) branch), as well as my new code. in the [`main`](https://github.com/lfils658/JDip/tree/main) branch.

## The Plan

We will use some of the original components to create a new web portal. 
NOTE: The original component will be marked with a tribute to Uncle J. 

Features:


New Code                                       | Recycled Original Code                         
---------------------------------------------- | ------------------------------------------------
Create an account (Users)                      | Google Search (May violate Google TOS)           
News feed                                      | Games (because they are still cool)              
Weather feed                                   |                                                  
Quick access links                             |                                                  

There will also be some code to be archived. We could possibly repurpose this code in the late stages of the project:

Archived Code                                  | Possible Repurposement
---------------------------------------------- | ----------------------------------------------- 
Shoutbox                                       | Forums 
Guestbook                                      | Forums
Other stuff (Image generator, etc.)            | Tribute Page

## The Process
### Execution of The Plan

1. Organize code in an "old" and "new" file tree
2. Dump Internet Archive data into the "old" folder
3. Organize the "new" folder into the planned file tree below...
4. Start writing code, pulling features from the "old" section
5. Finailize code

### Planned File Tree

    | Lfils/JDip/
    |  | Old
    |  |  | (Internet Archive Data)
    |  | New
    |  |  | Home
    |  |  |  | Homepage.file (includes search, shoutbox, quick links)
    |  |  | News
    |  |  |  | Newsfeed.file
    |  |  | Weather
    |  |  |  | Weather.file
    |  |  | Components
    |  |  |  | images
    |  |  |  |  | (images here)
    |  |  |  | scripts
    |  |  |  |  | (scripts here)
    |  |  |  | css
    |  |  |  |  | (css here)
    |  |  |  | other
    |  |  |  |  | (other files here)
    |  |  | Games
    |  |  |  | games.file
    |  |  |  | (Games here)
    |  |  | AccountSettings
    |  |  |  | AccountSettings.file

## IMPORTANT
Some portions of the original code have been exempted from the repository because they contain confidential information.
