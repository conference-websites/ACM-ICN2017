---
layout: default
title: Accommodations
group: Venue

hotels:
- id: bestwestern
  name: Best Western Plus
  url: http://www.si-hotel.com/preise.aspx?lang=en
  address: Hotel Steglitz International, Albrechtstr. 2, 12165 Berlin, Germany
  distance: 2.2 km
  rating: 4
  reservation-info: Reservation code is "ICN17". Use link below or contact <a href="mailto:info@steglitz.bestwestern.de">info@steglitz.bestwestern.de</a>.
  reservation-link: https://www.cbooking.de/v4/login.aspx?id=steglitzinternational&lang=en
  amenities: [Free WiFi, Free breakfast buffet]
  rates: [80 EUR single, 105 EUR twin or double room]
  deadline: July 24, 2017
  map: https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2431.250353526197!2d13.319120716152844!3d52.4564932798023!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47a85a85dcb704d9%3A0xbb313ed96f89dbfb!2sBEST+WESTERN+PLUS+Hotel+Steglitz+International!5e0!3m2!1sen!2sde!4v1475247214545
---

# {{ page.title }}

The main conference venue is the [Computer Science Building of Freie Unviersit&auml;t Berlin](venue.html).
Below is a list of nearby hotels with special offers for conference attendees.

{% for hotel in page.hotels %}
{% include hotel.html %}
{% endfor %}
