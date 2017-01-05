Aim of the project is to share tools that I use for creating GCP based solution architecture diagrams. [SOLUTION ICONS FOR ARCHITECTURAL DIAGRAMS](https://cloud.google.com/icons/) provides : 
- a set of presentation templates
- downloadable digital assets. 
- link to LucidChart that provides native GCP support

Being more of a [draw.io](https://www.draw.io/) user myself, I have created some custom libraries from the published digital assets (icons in PNG/SVG format).  

When loaded into your draw.io environment, you can then download icons from a pallet that shows up on the left side of the window.

!([https://raw.githubusercontent.com/n0531m/gcp_diagram_tools/master/Screen%20Shot%202017-01-05%20at%2023.29.38.png])

Some work to do :
- File names and icon section title seem to be linked in some way. When I created the libraries I have used section titles such as " GCP Icons / Products & Services / Developer Tools" (I know... its long...)  However, the "/" or "&" and replaced with "_" when storing as files. (which is understandable). You might have to rename the sections yourself. 
- File name being reflected to section title, I did not put any extensions. Adding ".xml" to all files would have made it more obvious. Need to find out what are the best practices here.
- Each section is a separate file. this means you have to load 19 files to load them all...  ideally there should be one file that will show up as 19 sections but I have not found a way to do that.

any feedback is welcome.


