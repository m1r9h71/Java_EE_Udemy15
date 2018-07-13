# Java_EE_Udemy15
Nature of Stateless Session EJB
#If EJB is declared as @stateless you can declare 6 FlightService objects fs, fs2, fs3, fs4, fs5, fs6
#give each a location fs.setFrom("London").... fs6.setFrom("Waterford")
#Use out.println(fs.getFrom()); for each setFrom statement
#It is stateless so allocates the same bean for each and prints off the list
#Small demeonstration into stateless sessions

#Prints: The flights details servlet has been called.....
London
Rome
New York
Paris
San Francisco
Waterford to screen
