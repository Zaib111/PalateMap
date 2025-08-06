PalateMap is a hackathon project created by Pranav Patnaik, Praneeth Suryadevara and Shahmeer Khan for the APEERS Solstice Hackathon. 

Entering a new restaurant sometimes comes with a challenge — what should I order? Menus can often be confusing, filled with unfamiliar dishes that you are not sure you'll like. With PalateMap, our goal
was to simplify the food ordering process by leveraging the previous food items the user has rated. 

Using our mobile camera component, we use Optical Character Recognition (OCR) to scan and understand the contents of the menu. Then, we embed the menu's dishes as vectors, with components such as spice, sweetness, grain, meat content, etc. These vectors are then compared to those of dishes the user has rated highly in the past, providing a similarity score and percentage
to them that the user can use to make an informed choice. PalateMap works as a feedback loop — the more dishes you rate and add to your personal database, the stronger the palate connections get.

This project was built with Python and Flask, with Firebase handling authentication.


Demo Video: https://www.youtube.com/watch?v=-3WmyYZqW9w&pp=ygUYcHJhbmF2IHBhdG5haWsgcGFsYXRlbWFw0gcJCa0JAYcqIYzv

Hackathon Link: https://apeers-solstice.devpost.com/project-gallery
