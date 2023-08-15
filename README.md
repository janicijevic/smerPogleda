### This paper was featured at the Petnica Science Center conference "Korak u Nauku" on 10 Dec 2020

# Abstract

## Estimating Gaze Direction With a Single Fixed Web Camera

This paper presents and evaluates a software solution for eye gaze tracking in real-time using a fixed RGB web camera, the likes of which can be found in many modern desktops, laptops and smartphones. The algorithm initially locates the face on an image and isolates the eye regions. To estimate the iris center on the eye region two methods are proposed: center of mass and circle approximation. An eye vector, which describes the position of the iris center relative to the inner eye corner, is formed. A mapping function is used to relate a given eye vector to the corresponding gaze point on the user’s screen, and it must be calibrated to each person. The two methods for iris center estimation are compared using the BioID database, where the results are presented as percentage of the images from the database for which the method is successful in estimating the iris center within a given threshold. The center of mass method performs better than the circle approximation method for a higher threshold with 95.5% compared to 92.2%, but worse for a lower threshold with 58.4% compared to 64.2%. Finally, for the comparison of the two methods when applied to the eye gaze tracking system the EOTT database is used. When using the center of mass method the average accuracy is 4.46°, which is better than 5.6° when circle approximation is used.

## Odredivanje smera pogleda korišcenjem jedne fiksne kamere

Predstavljen je sistem za odredivanje smera pogleda korisnika korišćenjem samo jedne RGB kamere kakva se može naći u svakodnevnoj upotrebi na kompjuterima, laptopovima i telefonima. Jedan od najvažnijih koraka u radu sistema je odredivanje centra zenice na slici, za šta su predstavljene dve metode: centra mase i aproksimacije kruga. Tačnost ovih metoda je ispitana na BioID bazi sa po dva praga tačnosti i dobijeni rezultati iznose 95.5% i 58.4% za prvu, odnosno 92.2% i 64.2% za drugu metodu. Greška konačnog rezultata sistema tj. smera pogleda dobijena je korišćenjem Eye of the Typer baze i iznosi 4.46° kada se koristi metod centra mase, odnosno 5.6° za metod aproksimacije kruga.

