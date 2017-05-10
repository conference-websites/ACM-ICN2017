---
layout: default
title: Accommodations
group: Local Information

hotels:
- id: bestwestern
  name: Best Western Plus (****)
  url: http://www.si-hotel.com/preise.aspx?lang=en
  address: Hotel Steglitz International / Best Western Plus<br> Albrechtstr. 2 <br> 12165 Berlin, Germany
  distance: 2.2 km / 1.2 miles <br/> conference venue is easy to reach via bus, 12 minutes door-by-door
  discount-code: <b>"ICN17"</b> (to get the rates above)
  reservation-info: Use link below and enter "ICN17" in the field "Room allotment code".
  attention: <b>If you arrive before September 24</b>, you cannot book your reservation using the link below. You need to contact the hotel directly via <a href="mailto:info@steglitz.bestwestern.de">info@steglitz.bestwestern.de</a>. Please note that the Berlin Marathon will take place on September 24, which may lead to higher rates for September 23.
  reservation-link: https://www.cbooking.de/v4/login.aspx?id=steglitzinternational&lang=en
  amenities: [Free WiFi, Free breakfast buffet]
  rates: [80 EUR single, 105 EUR twin or double room]
  deadline: July 24, 2017
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2431.250353526197!2d13.319120716152844!3d52.4564932798023!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a85a85dcb704d9%3A0xbb313ed96f89dbfb!2sBEST+WESTERN+PLUS+Hotel+Steglitz+International!5e0!3m2!1sen!2sde!4v1475247214545
  image:  images/hotels/bestwestern-si.jpg

- id: seminaris
  name: Seminaris Campus Hotel (****)
  url: http://www.seminaris.de/en/hotels/seminaris-campushotel-berlin.html
  address: Seminaris CampusHotel Berlin<br> Takustr. 39 <br> 14195 Berlin, Germany
  distance: 0.25 km / 0.16 miles
  discount-code: n/a
  reservation-info: Use link below.
  reservation-link: http://www.seminaris.de/en/hotels/seminaris-campushotel-berlin.html
  amenities: [Free WiFi, Free breakfast buffet]
  rates: [100-180 EUR single, 130-210 EUR twin or double room]
  deadline: The hotel has only very few rooms available.
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2431.2745534552105!2d13.291715316152885!3d52.456054979802225!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a85a6e3c087b7b%3A0xbb7374dc78069e69!2sSeminaris+CampusHotel+Berlin!5e0!3m2!1sen!2sde!4v1488037869542

- id: tba
  name: TBA
---

## {{ page.title }}

The main conference venue is the [Computer Science Building of Freie Unviersit&auml;t Berlin](venue.html).
Below is a list of nearby hotels.
We blocked a sufficient number of rooms in the Best Western Plus.
The location of the hotel provides a nice tradeoff, it is closely connected to both the conference venue and the rest of the city.

{% for hotel in page.hotels %}
{% include hotel.html expanded=forloop.first %}
{% endfor %}
