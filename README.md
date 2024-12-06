# Aquiplicity2024
Aquiplicity (multiplicity image stacker)

This is a scaled down version of Aquiplicity I'm playing with in 2024 (no GUI)

The program is c++ for visual studios and uses OpenCV made by intel for graphics

WHAT PROJECT DOES:
Program takes images and stacks them, bringing attributes of all images to a master
image and combining them.  The first image is a baseline called image0.jpg
such as an empty picture of a landscape.  The other images have an actor like a woman
in the same exact landscape image (tripod taken for exactness) but the woman is in
different locations on each image.  The program stacks these images.

After the master image is created the program allows you to click-and-drag a lasso.
The image from the pixel you started from will bring back sections of just that image
so for instance if a piece of her dress didn't carry to the master image correctly, one
can fix any missing pixels for asthetic reasons.

click the mouse and drag a free hand selection with a lasso tool on the master image. 
 Whichever pixel the image is on at the moment of click will determine what image of the
 stack is picked to repair the image.  For instance,  even if ten images are stacked in 
this master.jpg, if the pixel from image5.jpg is clicked then after the lasso is drawn 
…that section of the image from image5.jpg is brought forward and becomes the permanent 
part of the master.jpg.  In this way we can patch any parts of the master image we do
 not like.  

WHY IS THIS USEFUL:
The idea is from my program creation in 2010 of a full GUI which was allot more complicated.
The origin was trying to automate the Photoshop 'multiplicity' trend at the time
making actors appear many times in the same image.

HOW USERS GET STARTED:
This is just the C++ code from my visual studios.  Also for source, you need to
install OpenCV from Intel or install.  If using the MSI install it's all given.
All images such as image0.jpg  image1.jpg image2.jpg must go into the working
directory of the program.  Image0.jpg is the baseline for the master image.

++ when using the MSI install for ALL USERS so it gets permissions needed

WHERE USERS GET HELP WITH THIS IDEA:
Email me at aquiline.photos@gmail.com for any comments or questions.  It may take a while
for a reply.  Be patient.

MAINTAINED BY

Enjoy !
Mr. Tracy Rose
