## Aesthetic and Technical Development of Tenant Talk:
# First Iteration: Paper Prototype
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/IMG_9597.JPG)
We created a rough paper prototype around our 4th week after we looked at existing projects. The main idea we gathered from this stage of the paper prototype was the importance of non-linear storytelling in the humanization of the process (compared to pre-existing products which are more like manuals). This was specifically done with the idea of the map, which explored this non-linear storytelling, with markers on maps, with stories attached to each point. 
<br>
# Second Iteration: Troy and Ethan’s Menu
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/Screenshot%202024-04-27%20at%2023.01.40.png)
<br>
With this idea in mind, Troy and Ethan came up with a second iteration which focused on the menu. The issue we had with this design was the inconsistency of the visual style. The team agreed that the aesthetic of the app was visually heavy, and so a more basic design was favored to allow greater focus on the content of the app. This iteration of design has the general flow of the app, but is still linear in nature which conflicts with our focus on non-linear narrative. There are aesthetic choices such as the scrapped paper which may add on to the zine aesthetic, however the specific choice of this specific image is questionable as a digital zine / app for housing tenants. 
<br>
# Third Iteration:  Figma App Prototype (ver.1) (https://www.figma.com/file/6Y7hizZOSErAj3zDalIT5Y/Figma-basics-(Ver.1)?type=design&node-id=1669%3A162202&mode=design&t=Sz3zlXzsMFR6kjmj-1)
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/Screenshot%202024-05-09%20at%2019.51.04.png)
<br>
The third iteration was also created in figma with the main focus of developing an actual  layout for the digital zine itself. One thing we kept from the previous iteration was the login system / menu, which conceptually exists to verify the validity of the stories themselves. For this iteration, I considered utilizing Marker Clusters to improve the visual simplicity when there are multiple points in the area. However this proved to be difficult for me to execute in javascript, and was therefore scrapped.
<br>
# Fourth Iteration: LeafletJS (TenantTales) (https://nu-digital-cultures.github.io/Trout/TenantTalkApp/Map%20HTML/index.html)
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/Screenshot%202024-05-07%20at%2011.27.02.png)
<br>
A visual product which focuses on the humanisation of storytelling beyond numerical rating systems. We aim to do this through personal stories and experiences of renting from students, collected through surveys or submission which they would be able to do on the app in future iterations (hypothetical). The main system revolves around the map as users who are planning to move close to the area, can look at certain points based on the experiences of other students, helping them to choose an area better suited for them. I used a GeoJSON data from https://martinjc.github.io/UK-GeoJSON/ and used the “Westminster parliamentary wards” for the area representation as it balanced the simplicity and complexity of the area borders whilst still being relatively accurate to area labels, on publicly available maps. 
<br>
# Fifth Iteration: Figma (TenantHandbook) (https://www.figma.com/proto/2I2GfgxQAwwokmIrc1A0Ha/TenantHandbook-Prototype?type=design&node-id=730-1303&t=BJbMM0HyC95CwbkS-1&scaling=scale-down&page-id=1669%3A162202&starting-point-node-id=730%3A1162&mode=design)
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/Screenshot%202024-04-30%20at%2013.59.16.png)
<br>
Our goal with the tenant handbook was to make a handbook about tenancy rights and laws which the tenants could reference and learn from not through just words, but from a more interactive and intuitive presentation. Inspired by the collage that Blythe put in, TenantHandbookIdeas.md I created a visually eye-catching and friendly design of a typical housing in Adobe illustrator, which I took to figma to develop a prototype. Each room has specific items that correlate with the information that students from our survey felt was important, and tenants can reference these information when accessing the app, and reference according to their needs or concerns.
<br>
# Sixth Iteration: Figma Final (https://www.figma.com/file/UmZ6oeoMOkU6QbWeR6pZTP/Tenant-Talk-(Ver.2)?type=design&mode=design&t=Sz3zlXzsMFR6kjmj-1)
![](https://github.com/soichiro331/soichiro331/blob/main/untitled%20folder%202/Screenshot%202024-05-09%20at%2019.50.23.png)

For this iteration, I made some small tweaks in the design of the app / zine to professionalize the looks. Such as adding gradients to the background. and icons to the menu buttons for easier understanding. I've also added a more final representation of what the map would look like, with poems, and artworks that groups together as a collage which users can scroll. This was then merged with the Tenant Handbook and Tenant Roundup and connected via the prototype feature to replicate the full function of the app / zine conceptually. 
<br>
# Technical Implications:
The submission process requires a server to receive and manage the data within the app which is hard to achieve and replicate with the knowledge in coding I have in coding right now. Realistically this would be done through a combination of javascript and php, and hosted on a website which mobile users can either visit via their search engine so updates can be done easily. However, at this current stage the best option without developing a php page will be to manually collect survey data with word of mouth and manual update.

