# Official Website of the Rancho San Joaquin Middle School National Junior Honor Society Chapter

Learn more about <a href="https://njhs.us">NJHS</a>.

epic gaming njhs website made by me

steps to customize website:
- change the file in assets/group-bg to your front page photo
  - in assets/styles.css change the .group-photo padding to be (image height / image width x container width) (your container width is probably 100).
- in members.html, change your member list to reflect your own club with your own images and bios (image files can be located in the assets/members folder)
  - images are scaled to 250px. make sure these images are square (don't worry about making them circular, that's handled by the code)
- also in the assets folder, change the images on the front page to your own members.
- you can adjust the size of these images by adjusting the values for index-img in styles.css
- in calender.html change the calender widget to your google calender

to add/remove service projects:
- edit the text blurbs in index.html to update the front page. also make sure to appropriately update the images in the assetes folder (take them down when appropriate, to remove clutter)
- in the google drive folder named "Photos" (which the ranchonjhs gmail account has access to. ask mrs hartmann for credentials), create a new folder, with a text file named desc.txt, which contains a short blurb in HTML format
- add images if you want.
- done---the script automatically refreshes at like 2 in the morning, but if you happen to be impatient, go into the google script and run the function named refresh()

in case you want to edit the website, the ranchonjhs gmail account has access to all the google assests (namely scripts)

if the domain stops working, remind mrs. hartmann to go to porkbun.com and renew the subscription


ranchonjhs website was coded by dominic huang and timothy chen
