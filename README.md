# portfolio
Web portfolio for Coder Academy bootcamp assessment

Link to Github repository: https://github.com/gwencitaaa/portfolio
Link to Trello board used for project management: https://trello.com/b/xgYfmk1g/ca-portfolio-project
Link to Figma used for this project: https://www.figma.com/file/X0WffcvqB6vdxoMvjykclPE6/Portfolio-Moodboard?node-id=0%3A1

*Purpose*

The purpose of this website is to function as an online portfolio, displaying both my personality and technical skills/experience. The audience is Coder Academy for assessment, but also the wider tech community and potential employers. 

*Target audience*

I see the target audience as predominantly being two groups:

- Coder Academy instructors who are evaluating it as part of the assessment for the bootcamp
- potential employers.

While peers are also part of the audience, I wanted to keep potential employers front of mind. 

For this audience of potential employers, I wanted to keep the design minimal and uncluttered, with a fun navigation pattern. I liked the idea of having oversized icons that represented each page of the website as the main navigation tool and displaying them centred on one half of the page rather than at the bottom or top (or side) in a more traditional design. 

*Functionality*

The website has four main pages
- Home (default)
- About, containing more details about me as a person
- Contact, containing links to Twitter and Linkedin and a contact form
- Work, containing a link to Github and examples of other work demonstrating who I am (writing and music).


It also has a live chat widget that appears on every page. 

*Tech stack*

The site is built using HTML and CSS. I already owned a domain name from Namecheap, and my classmate, Tim, helped me do the configuration so I could deploy it using Gitpages. 

Screenshot of A records in Namecheap

![Screenshot of A records in Namecheap](images/Day&#32;4/images/Screenshot_Namecheap_Arecords.png)

Screenshot of matching github page domains

![Screenshot of Github domains](images/Day&#32;4/images/Screenshot_Gitpages_IP_addresses.png)

*Search function*

While I originally intended to have search functionality, an instructor asked about it and I re-evaluated and decided it isn't a core function of a portfolio website. Therefore, there is no search function in the website. 

*Use of icons*

Each page is represented by an icon. I designed these icons so the style was consistent with the rest of the site's look and feel. I wanted them to be simple, modern, and solid.

The icons are as follows
- Home page: house
- Work page: suitcase
- Contact page: envelope
- About page: information symbol in circle

Early original design of icons in Figma

![Screenshot of icon design](images/Day&#32;2/images/Figma_Icons.png)

*Update to icons*

To make the icons more uniform, our instructor Aaron recommended Font Awesome. This was great as I could control the colour and size much more easily. I spent time on Day 3 replacing the icons with Font Awesome Icons and sizing/colouring them. 

New icons from Font Awesome

![Screenshot of updated icons](images/Day&#32;4/images/Screenshot_UpdatedIcons.png)

Each icon that is clickable enlarges slightly when it is hovered over to let the user know it can be interacted with. The icon of the page a user is on sits in the middle of the page with its label visible. 

*Icon labels*

While the icon in the centre of the page representing the current page has a visible label, I decided to keep the other icons that were for navigation around the site without labels. The home page invites the user to 'jump around by clicking on the icons' and I think this invitation combined with the oversized nature of the icons means a user will intuitively feel these are for navigation. 'Relative size aids noticeability' (https://www.nngroup.com/articles/icon-usability/) for icons and there is no other visible navigation elsewhere in the pages. I believe this design decision is almost adding in an element of gamification to entice the user to play. 

This ignores the icon usability guidelines around having a label, but I weighed up the decision carefully and also trialled design with labels (code and screenshots below), but didn't like how it cluttered the UI and removed the feeling of delight experimenting. 

Code snippet for labels on icons

![Screenshot of code snippet](images/Day&#32;5/images/IconLabelCodeSnippet.png)

Design with labels on navigation icons (larger font size)

![Screenshot of webpage showing labels on icons](images/Day&#32;5/images/Icons_LargerLabels.png)

Design with labels on navigation icons (smaller font size)

![Screenshot of webpage showing labels on icons](images/Day&#32;5/images/Icons_SmallerLabels.png)

Finally, in my user testing, I checked whether the icons I had chosen were recognisable symbols and they were. This was a test recommended as best practice in the usability guidelines from the Nielsen Norman group. 

*Font planning*

I looked through Google fonts for a while, and did searches on what fonts were readable and popular for design. 

I love looking at fonts, so I was happy to just find ones I liked and see how they looked. 

I thought Oswald made a bold statement and was also readable. But when I saw it on the page, I didn't like how it looked, so I tried to find a font with more curves. I settled on Rajdhani. It has a modern, stylised feel but is still readable and clean.

Oswald font

![Screenshot of Oswald font](images/Day&#32;4/images/Screenshot_FontPlanning.png)

Rajdhani font

![Screenshot of Rajdhani font](images/Day&#32;4/images/Screenshot_FontPlanning_Rajdhani.png)

*Bottom navigation on mobile/tablet*

On the mobile/tablet layout, a bottom navigation pane was planned during the design process. This was to facilitate one-handed use, meeting the UX criteria of Reachability. It was also a design choice based on current research in UX, specifically on the 'Touch' principle. I read that one-handed use is more common than thought, and that good design should consider functions sitting on the bottom within the 'thumb zone' (left, combined and right). 

Bottom nav bar design in Figma

![Screenshot of nav bar design](images/Day&#32;2/images/Figma_Navbar.png)

However, after user testing, this design didn't work well. Therefore, I removed the bottom navigation on mobile/tablet and kept the icons on the right hand side of the page, making them smaller in size. The icons are within reach of the thumb (in the 'Natural' and 'Stretch' zones), which was a consideration I had for usability, since around half of users use a phone with one hand. The heatmap below shows these zones in heat maps for design on iPhones. 

Thumb Zone Heat map for iPhones (since 2007)

![Thumb Zone heat map for iPhones](images/Day&#32;5/images/ThumbZones.png)

Source: http://scotthurff.com/posts/how-to-design-for-thumbs-in-the-era-of-huge-screens

*Hamburger menu*

On a mobile view, I originally designed a hamburger menu to sit in place of the two extra pages. The decision to use a hamburger menu instead of two more icons was based on three main reasons. 

Firstly, I wanted to allow for 'fat fingers and bad eyesight'—in other words, to use the principles of human-centred design for an easy to navigate UI. I also intended for there to be ample space for contact patches, since they vary in size and shape. Finally, I wanted a clean UI, and when I trialled five icons along the bottom, they were too close in distance and the UI looked cluttered as a result. 

Hamburger menu design 

![Hamburger design plan](images/Day&#32;2/images/Figma_HamburgerMenu.png)

Update on Day 3: Hamburger menu removed 

After I removed search, I was able to remove the hamburger menu, allowing navigation to be done using the icons representing each page. This is good from a usability perspective, as it removes a step for the user and keeps the options in the UI visible and therefore easier for users to navigate.

**DAY 1 SPRINT**

My aim today is to
- set up Trello
- set up Github repo
- complete copy writing
- complete selection of colour theme
- design wireframes
- take screenshots of progress 
- minimise image sizes of screenshots
- add screenshots into README
- if time, bring forward some of tomorrow's tasks e.g. spike.

*Project management*

*Github*

I set up Github this morning and started adding planning notes into the README file. I've also created an Images folder to store images in.

*Figma*

I created some colour pallettes last night from a Klimt painting that I love (see screenshot below). The feeling of dark colours with bright highlights was what I felt like playing with intuitively for my portfolio. 

Colour palette planning in Figma

![Colour pallettes from a Klimt portrait](images/Day&#32;1/Figma_ColourPalettes.png)

When I thought about it, it was the colours from a photo of a big city after rain at night, with neon lights and blurred streelights that I was trying to get. I remembered a wall decorated for a Wed Anderson movie where there was a night scene with lights where the city buildings were like paper cut outs. I loved it so much, so I tracked down a picture of that and found a couple others for inspiration. I added these into Trello so I could refer back to them. 

Update on colour palette

I needed more contrast and wanted brighter colours (like the aurora borealis or the neon lights I'd thought of earlier). Played with those and I've decided that this is the colour palette I'll start wireframes with. Maybe with a more fluro yellow... :)

Colour palette planning in Figma—Take 2!

![Colour pallettes from aurora borealis](images/Day&#32;1/Figma_ColourPalette_Take2.png)


*Trello*

I set up Trello with days organised as sprints with daily retrospectives up until Friday (see screenshot 1. I've allocated tasks to each day and labelled each rubric criteria with the days that its areas are being worked on. Screenshot 2 shows Day 1 (Tuesday's) tasks. 

Screenshot 1: Day 1 trello set up

![Screenshot of Trello on Day 1](images/Day&#32;1/Trello_Day1_screenshot.png)

Screenshot 2: Day 1 task card—inspiration

![Screenshot of Trello card for Day 1](images/Day&#32;1/Trello_Day1_TaskCard_Inspo.png)

Screenshot 3: Day 1 task list

![Screenshot of Trello task list](images/Day&#32;1/Trello_Day1_TaskList.png)


*Portfolio requirements*

Notes from Leah when going through rubric: 
- try a spike (e.g. 2 hours) early on to consider whether technically the design is appropriate given the timeframe and assessment parameters
- RE images: minimise image sizes, try 1MB or lower if poss. 
- By tomorrow lunch, get approval on design
- To try multiple browsers, go to diff. browser e.g. Firefox, clear cache and load it in to check loading time / how fonts work etc. 
- RE font, 'less is more', e.g. one heading font / one other font or all same font with diff. weights
- Could try Hemgingway site
- RE tables, use tables in readme (Leah to clarify)
  
*Draft copy*

> Overall vibe/tone

- Friendly, conversational
- Light-hearted and playful
- Joy filled with touches of darkness

> Overall look
- dark
- colourful verging on fluro accents

> Home page

Hi! I'm a curriculum developer in Melbourne, Australia. After 10+ years working in education, I'm training to be a web developer—my dream job! 

I do other stuff too, like
- wite copy
- write content
- edit
- volunteer
- teach girls to code
- speak.

Good design and art lights me up, as does my Devon Rex cat, Admiral Nelson. 

My main drive is to leave the world a better place than when I came into it.


> About this site

This website is a portfolio for my Coder Academy web development bootcamp assessment. The brief was to design then deploy a well-designed and functional portfolio website.

> History of internet (w/graphic?)

> Work

Code structure planning

I went through a couple of ways to do this with both Harrison and Aaron, and eventually settled on doing the whole webpage as a grid with two columns in a container class. Within the left half, there are divs for the avatar and text and within the right half, there is a flex box for the icons which act as the navigation tool. 

Screenshot of code structure plan (in Figma)

![Screenshot of Figma design](images/Day&#32;1/Figma_CodeStructure_Overview.png)

*End of day 1 update*

- Copy not finished bc Aaron recommended getting wireframes done earlier to get approval. 
- Got approval for design after showing home screens and 'About' screens in Figma. 
- I added in an image of the aurora borealis for visual interest after trying block colours, a triangle shape for text and a speech bubble, but finding all of these were too strong or busy to look good. 
- For the layout, I brainstormed what pages I needed while looking at the rubric, and settled on 
- - 'Contact' for links (Github / linkedin) and contact details
- - 'About' for more info about me and info about the page
- - 'Work' for examples of my work / experience / skills
- - 'Home' for home page with tiny hello message and icons. 

Checklist at end of Day 1

All tasks except copy were completed. I will complete those today or tomorrow. 
![Screenshot of checklist at end of Day 1](images/Day&#32;1/Checklist_EndDay1.png)

*Icons*

I created icons for each page (About, Home, Work, Contact) on the website by using the shapes in Figma. I made these simple, recognisable images, taking into account the principle of familiarity/recognisability in User-centred design.

Screenshots of design 

Early designs that were scrapped

![Screenshot of nav pane design](images/Day&#32;1/Figma_EarlyDesign_Navpane.png)


![Screenshot of layout designs](images/Day&#32;1/Figma_EarlyDesign_scrapped.png)

Approved Home screen designs

![Screenshot of Home screens design](images/Day&#32;1/Figma_HomeScreen_Approved.png)


Approved About screen designs

![Screenshot of About screens design](images/Day&#32;1/Figma_AboutScreen_approved.png)

Updated Home screen designs (post-approval)

![Screenshot of Home screens design 2](images/Day&#32;1/HomeScreen_Design2.png)

Updated About screen designs (post-approval)

![Screenshot of About screens design 2](images/Day&#32;1/AboutScreen_Design2.png)

*Day 1 retro*

I did a mini-retrospective on Day 1. I need to stick to my plan so I'm not stressing about time. I've been worrying that my brother is coming down as a surprise for three days and I won't have time, but I stepped out the project management stages and it will be okay if I trust the process. 

Screenshot of retro

![Screenshot of Trello card](images/Day&#32;2/images/Trello_Day1_Retro.png)

**DAY 2 SPRINT**

My goals today are 
- to get most of my HTML structure completed 
- find out how to link pages within a website
- how to use svg files. 

I converted the uncompleted tasks from Day 1 into their own cards and they're sitting in Day 2 as well now. 

Screenshot of Trello board, Day 2

![Screenshot of Trello board](images/Day&#32;2/images/Trello_Day2_start.png)


Screenshot of Trello task list, Day 2

![Screenshot of Trello task list](images/Day&#32;2/images/Trello_Day2_TaskList.png)

*Code structure*

This is the plan for my code structure. I checked with Harrison and he thought a div might be better for the icons in the middle of the right half of the page (I wasn't sure what would be best). So now I'm planning to try a flex box for the search icon positioning, and divs for the rest of the sections. 

I tweaked the design last night and Harrison was happy for it to go ahead. 

For the icons, I'll be exporting them as svgs and using them that way. 

Screenshot of code structure planning

![Screenshot of Figma layout](images/Day&#32;2/images/Figma_CodeStructure_Plan_Day2.png)

*Sitemap*

I created a simple Sitemap using www.gloomaps.com. I had to think about how the pages were related and I'm still not sure it's right. I'd like to learn more about site architecture and systems design in future. It's like a fun mix of visual representation and content structure, which reminds me of what matters when writing curriculum. 

![Sitemap screenshot](images/Day&#32;2/images/Sitemap.png)

*Design of other screens*

I created wireframes for the hamburger menu (phone/tablet only) and other main screens.

Work page wireframe

![Wireframe of Work page view](images/Day&#32;2/images/Figma_WorkScreen_wireframe.png)

Contact page wireframe

![Wireframe of Contact page view](images/Day&#32;2/images/Figma_ContactScreen_wireframe.png)

*End of Day 2 update*

I needed a lot of help to get the HTML structure in place in terms of files and what order to put code in (and whether flex or grid is better).

However, the home page is on its way to being designed and is almost completely stucutured. 

I am considering scrapping the search functionality from the MVP on advice from an instructor and considering how long it took me to do one page without search.

*Retro*
What I felt most strongly from my retro for Day 2 is that I need to stop feeling stupid when I ask for help. It isn't helping and I learn faster by watching someone else then copying. Although that doesn't seem to be how they want us to learn here, I'm kind of sick of beating myself up for it. 

Trello card for retrospective, Day 2

![Screenshot of Trello card](images/Day&#32;2/images/Trello_Retro_Day2.png)

Overall, I'm on track except I was hoping to get more HTML code done by now. 

Trello board at end of day 2

![Screenshot of Trello card](images/Day&#32;2/images/Trello_Day2End.png)

**DAY 3 SPRINT**

Trello board at start of day 

![Screenshot of Trello board](images/Day&#32;3/Images/Trello_Board_Day3.png)

Task card at start of day

![Screenshot of task card](images/Day&#32;3/Images/Trello_TaskCard_Day3.png)

*Changes to structure*

I've removed the search functionality (as updated higher in this doc) and also the hamburger menu, since the icons will now fit. 

I'm struggling to position the text with the center icon and also to position text. I've spent a long time looking this up and getting help and it's still not fixed. 

*Update at end of Day 3*

Text labels for icons are fixed. I needed to use transform and play a lot with the numbers. I'm getting used to using inspect but it's not easy to transfer across to code since it resizes the screen. 

**DAY 4 SPRINT**

Something has gone super wrong with Git and it's not recognising local. Hopefully I don't lose all my stuff. I wasn't able to commit my changes and it keeps wanting to add all of my files. I tried to add local again since it wasn't showing, but it's still not working. Update: restarted and all good. Phew! 

*Day 3 retro*

I did a glad/sad/mad retro for Day 3, one of the ones from Atlassian's Team Playbook that I haven't tried. I'm pretty sick of almost crying constantly but still haven't figured out how not to. Maybe Day 4 is the day!

Trello Day 3 retro

![Screenshot of Trello card](images/Day&#32;4/images/Trello_Day3_Retro.png)

*Day 4 tasks*

I checked off everything but two things from yesterday's list. I still need to work out three elements:
- the hover function for my icons
- media queries or code for resizing screens for different devices
- (ideally) making the form wider.  

Trello board, Day 4

![Screenshot of Trello board on Day 4](images/Day&#32;4/images/Trello_Day4_board.png)

Trello Task list, Day 4

![Screenshot of Trello card task list](images/Day&#32;4/images/Trello_TaskList_Day4.png)

Testing on other browsers and devices

I've tested so far on:
- Desktop using Safari browser
- Desktop using Chrome browser
- Desktop usng Firefox browser
- Resizing each of these three browers on desktop
- iPhone 6 on Safari browser

While Safari and Firefox browsers render the font differently, I am leaving it at this point because the design features still remain. 

View on Chrome (desktop)

![Screenshot of webpage on Chrome](images/Day&#32;4/images/Screenshot_Chrome_pageview.png)

Page view on Safari (desktop)

![Screenshot of webpage on Safari](images/Day&#32;4/images/Screenshot_Safari_pageview.png)

Page view on Firefox (desktop)

![Screenshot of webpage on Firefox](images/Day&#32;4/images/Screenshot_Firefox_pageview.png)

Page view on iPhone (Safari)

In iPhone, the text becomes scrollable and the bottom margin changes so that it doesn't overflow onto the bottom nav bar which appears for the icons which are along the right side of the page in desktop/larger screen-sized tablets. 

![Screenshot of webpage on iPhone in Safari](images/Day&#32;4/images/Screenshot_iPhone_pageview.png)

*End of Day 4 Update*

*Hover*
I successfully added in a small effect for when icons are hovered over for navigation—they enlarge slightly upon hover and go back to their normal size when the mouse moves away. 

*Live chat*

I remembered the live chat I used to use when I built a blog for a learning centre, so I thought I'd add it in as it's super simple to use. I changed the colours so it matched my theme and it's now ready. I love it!! It's from tawk.to.

Screenshot showing Tawk.to live chat icon (in top right of all page views across devices)

![Screenshot of page view](images/Day&#32;4/images/Tawk_LiveChat_Icon.png)

Screenshot of live chat window

![Screenshot of live chat window](images/Day&#32;4/images/Tawk_LiveChat.png)

*User testing*

I got two users to have a look around the site on their phones. One found it quite awkward to scroll as he had larger fingers than I do and thought the icons at the bottom weren't helpful in this case because they were too close to the scrolling. As a result, I removed the bottom navigation.

*Code changes after user testing*

When the screen size reduces (around tablet size but also if someone shrinks their browser on desktop), the icons on the right hand side of the page now stay there, but reduce in size. 

I was then able to reduce the bottom margin on the left, so more text fits into the page when the screen size reduces. This looks better and means less scrolling. 

*Day 4 retro*

I am really happy with the progress. I finally felt good about it today for the first time. 

![Screenshot of Trello card](images/Day&#32;4/images/Trello_Retro_Day4.png)

Trello board, end of day 4

![Screenshot of Trello board](images/Day&#32;4/images/TrelloBoard_EndOfDay4.png)

**Day 5 SPRINT**

*To do*
Today, I need to:
- check what I've done carefully against the rubric
- fill in gaps
- get the Work page looking good at any size (the color boxes look weird when reduced in size)
- finalise design elements
- write the short responses to the 3 questions. 

*Audio files*
Today I had headspace to think about how the site is reflecting my personality, as required in the brief. I thought it would be nice to have an audio file on the welcome and about pages and looked into this. 

I found that using 'audio' and 'controls', it's now possible to add audio files into a webpage with HTML. So I recorded a couple of audio files using vocaroo.com (screenshot below) and downloaded them, then added them to my source files. 

Vocaroo

![Screenshot of vocaroo.com](images/Day&#32;5/images/Vocaroo.png)

I put a class on the audio control so I could change the size and played around on the different browsers and my two devices (MacBook and iPhone) until the size fit well on the page. I also added a bottom margin so it wasn't squashed up against the text under it. 

Home page with audio (full size)

![Screenshot of webpage](images/Day&#32;5/images/Screenshot_HomeWithAudio.png)

Home page with audio (reduced screen size)

![Screenshot of webpage](images/Day&#32;5/images/Screenshot_HomeWithAudio2.png)

Work page update
I removed the boxes and tried doing plain white text, as this looks clean on the other pages. I like it. I also inserted horizontal lines to get more definition between each link and added a small explanation for each one. I like the look much more. 

Work page with white text instead of colour boxes

![Screenshot of work page on website](images/Day&#32;5/images/WorkPage_NoColourBoxes.png)

*Accessibility testing*

I wanted to test for accessibility so I tried a couple of online tests—Web Accessibility by Level Access (www.webaccessibility.com) and WAVE, Web Accessibility Evaluation Tool (wave.webaim.org). I really liked the WAVE tool, because it had clear explanations as pop ups on the layout of the site. 

There were a couple of changes I could make immediately, which I did. I didn't change the icons by adding text as both tools recommended because I need to look into that more, but I will do this in future. 

Changes made for accessibility
- added a page title for each page
- added an h1 to each page
- added an alt tag for the audio files

Screenshot of WAVE tool analysis

![Screenshot of accessibility test of webpage using wave.webaim.org](images/Day&#32;5/images/WAVE_AccessibilityTest.png)

Screenshot of Web Accessibility analysis

![Web Accessibility test screenshot](images/Day&#32;5/images/WebAccessibilityTest.png)

Color blindness testing

To check that the site had enough contrast visually for people with colour blindness. After doing some research on what I could use, I installed a chrome extension, RGBlind, which simulates two common types of red/green colour blindness
- Protanopia ("red blind")
- Deuteranopia ("green-blind").

Screenshot of webpage viewed with Protanopia simulation

![Screenshot of webpage viewed with Protanopia simulation](images/Day&#32;5/images/RGBlind_ProtanopiaSimulation.png)

Screenshot of webpage viewed with Deuteranopia simulation

![Screenshot of webpage viewed with Deuteranopia simulation](images/Day&#32;5/images/RGBlind_DeuteranopiaSimulation.png)

I double checked this result on another site, https://www.toptal.com/designers/colorfilter/, to confirm the simulation was the same. At this site I was also able to see what two more types of color blindness would see. The two other checks simulated
- Tritanopia (blue/yellow colour blindness)
- Achromatopsia/Greyscale (partial or total absence of colour vision).

Screenshot of webpage viewed with Tritanopia

![Screenshot of webpage viewed with Tritanopia](images/Day&#32;5/images/Toptal_TritanopiaSimulation.png)

Screenshot of webpage viewed with Achromatopsia

![Screenshot of webpage viewed with Achromatopsia](images/Day&#32;5/images/Toptal_GreyscaleSimulation.png)

The design elements were all visible in these different simulations, so I made no changes to the design based on colour blindness testing.

*Typography*

I did some research on what font size was best practice. While some sources said 16px was appropriate, others suggested 18px was better if there was a chunk of text. I was on 17px, so changed it to 18px and was happy with how it looked. I think that's better than 16px for people that might struggle with their eyesight. 

For forms, there is apparently an effect if the input text is smaller than 16px where iOS browsers will zoom in on the left of the text input, forcing a user to zoom out. While mine resizes and looked okay on phone, it did seem to obscure the placeholder text, so I changed the font size of the form inputs to 16px. 

My line height was already 1.5rem, which was best practice, so I didn't change that. 

Sources:

https://howtogetonline.com/web-typography-best-practices.php

https://learnui.design/blog/mobile-desktop-website-font-size-guidelines.html

https://www.websitebuilderexpert.com/designing-websites/pick-best-font-style-for-website/

https://www.fonts.com/content/learning/fontology/level-2/making-type-choices/choosing-display-typefaces-for-the-web

*Updated Sitemap, Day 5*

Since I removed the search function, the sitemap has now changed from the original that was planned and shown in the previous screenshot.

I learned a little more on Sitemap index files and used a free sitemap generator (https://www.xml-sitemaps.com) to generate my site's XML file. I uploaded this file to my root folder. 

Screenshot of XML file for shewriteslikeadream.com

![Screenshot of XML file](images/Day&#32;5/images/Screenshot_SitemapFile.png)

**DAY 6 SPRINT**

*HTML validation*

I tried validating my code using an online checker. I wanted to anyway, but I also still can't resolve the bottom section on the webpage outside of the html container appearing as white space and I hoped this might help, as looking for solutions elsewhere didn't. One of the suggestions I read was helpful—to put red borders around everything in CSS.

Screenshot of debugging with red borders

![Screenshot of debugging a webpage using red CSS borders](images/Day&#32;6/images/DebuggingRedBorders.png)

Screenshot of online code validation analysis

![Screenshot of online HTML validation](images/Day&#32;6/images/HTMLValidation.png)

I was unable to solve the white bit, but I cleaned up my code of a couple of extra tags and removed the audio alt tag as suggested.

*Experimenting*

I had a go at creating ASCII art using https://art.pixlab.io/ and looked into creating an easter egg. I thought it would be fun to do if I could, so I tried using a couple of different photos of my cat. I couldn't get the ASCII art to look good or work as an easter egg quickly so I dropped it but enjoyed the experiment.  

![Screenshot of ASCII art experiementation](images/Day&#32;6/images/Screenshot_ASCIIExperiment.png)

**Short answer Q and A from assignment brief**

*Question 1*

Describe key events in the development of the internet from the 1980s to today

*My answer*

A network of computers connected using phone lines—ARPANET—existed in the 1980s. But this network could not communicate with others (Featherly 2019). Thus, a way for 'packets' of information to move between computers called the Transfer Control Protocol/Internet Protocol (TCP/IP) was developed (Cert & Khan 1974), which has formed the foundation of the internet since 1983.

Diagram of how TCP/IP works (Anonymous n.d.)

![Diagram of TCP/IP](images/Day&#32;5/images/TCP:IP.jpg)

The decentralised Domain Name System (DNS) came next (Mockapetris 1983), allowing fast translation of IP addresses. A short time later, Tim Berners-Lee conceived and developed the World Wide Web, HTML, HTTP and URLs (Berners-Lee 1989). 

Mobile phones evolved into smartphones, putting the internet in people's pockets.

Mobile phone development over time

![Images of mobile phones over time](images/Day&#32;5/images/MobilePhone.jpg)

Social media grew in popularity from 2003 onward.

Timeline of social media 

![Infographic on the history of the internet from Behance](images/Day&#32;5/images/Internet_History_Infographic.jpg)

Today, more than 50% of adults around the world use it (see graphic below).

![Social media use around the world graphic](images/Day&#32;5/images/Social&#32;media&#32;use.png) 

Faster internet speeds have meant constantly growing demand for data (see Table 1).

Table 1. Growth in data use over time
![Mobile phone data use growth](images/Day&#32;5/images/DataGrowth.png)

Today, the connectivity of the early internet is being extended further with the Internet of Things, AI and big data. This period is known as Industry 4.0.

![Industry 4.0 graphic](images/Day&#32;5/images/Industry4.0.png)

    Word count: 150 words excluding citations

*References*

Berners-Lee, T 1989, 'Information Management: A Proposal', *CERN*, [project proposa], viewed 24 March 2019, <https://www.w3.org/History/1989/proposal.html>.

Cert, VG & Kahn, RE 1974, 'A Protocol for Packet Network Intercommunication, *IEEE Transactions on Communications*, vol 22, no. 5, pp. 637-648.

Featherly, K 2019, 'Arpanet', *Encyclopaedia Brittanica*, viewed 24 March 2019, <https://www.britannica.com/topic/ARPANET>.

Mockapetris, P 1983, 'Domain Names - Concepts and Facilities', *Network Working Group* [Request for Comments document #882], viewed 24 March 2019, <https://tools.ietf.org/pdf/rfc882.pdf>.

*Question 2*

Define and describe the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers 

*My answer*

Let's take you accessing your email as an example of how the internet works. 

You open up a browser such as Chrome, and type in your email’s domain name, e.g. www.gmail.com. The web browser then needs to find gmail’s IP address.

The IP address could be in your computer's cache already, but if it isn't, the web browser will request that information from DNS servers. 

Once that’s done, your computer can request to see the webpage from the web server. The web server receives your request and responds—hopefully by sending you the page you want. Otherwise, it will send you an error message. 

Finally, your browser will render the page as it should look to humans, after compiling all of the packets of information that were broken up in order to be sent to you via IP and safely identified by TCP. And there’s your email! 

    Word count: 149 words

*Question 3*

Reflect on one aspect of the development of internet technologies and how it has contributed to the world today

*My Answer*

The aspect of internet technologies' development that I would like to focus on is internet technologies' capacity to affect positive societal change.

One serious issue facing society is the lack of gender equality. This limits the development of technology and society by excluding females or non-binary people from positions of power and authority where decisions are made. Technology can disrupt this situation. 

For example, women in 100 out of 173 countries are limited in their opportunities to work (The World Bank 2019). But access to the internet has facilitated education and increased employment opportunities for such women. Likewise, E-commerce platforms and online financial support have allowed these women to run online businesses where they would not otherwise had been able to (Bendall 2018). 

The impact of improving gender equality in the workforce is estimated to be an increase to the global GDP by $28 trillion (Council on Foreign Relations 2019).

    Word count: 148 words

*References*

Bendall, F 2018, *"Glimmers of hope": Five incredible global initiatives to benefit female entrepreneurs.* Smart Company, viewed 25 March 2019, https://www.smartcompany.com.au/finance/funding/global-initiatives-benefit-female-entrepreneurs/.

Council on Foreign Relations (CFR) 2019, 'Growing Economies Through Gender Parity', *Women and Foreign Policy Program*, [report], viewed 24 March 2019, https://www.cfr.org/interactive/womens-participation-in-global-economy/.

The World Bank 2019, 'Women, Business and the Law 2019: A Decade of Reform', *The World Bank*, [report], viewed 24 March 2019, http://wbl.worldbank.org/#.

**End of project**

I've completed all coding files and updated the README. All Trello cards are in 'Done'. 

![Trello board screenshot](images/Day&#32;6/images/Trello_Day6End.png)

*Presentation*

I created the same background effect for my presentation to keep it branded uniformly with the website and completed slides to talk through the design and build process. 

![Screenshot of presentation slides](images/Day&#32;6/images/PresentationSlideDeck.png)

*Final website look*

The web pages in their project submission state look as follows:

Home page

![Screenshot of Home page at end of project](images/Day&#32;6/images/Final_HomePage.png)

About page

![Screenshot of About page at end of project](images/Day&#32;6/images/Final_AboutPage.png)

Contact page

![Screenshot of Contact page at end of project](images/Day&#32;6/images/Final_ContactPage.png)

Work page

![Screenshot of Work page at end of project](images/Day&#32;6/images/Final_WorkPage.png)

