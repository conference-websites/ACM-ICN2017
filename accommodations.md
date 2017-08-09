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
  reservation-info: You need to contact the hotel directly via <a href="mailto:info@si-hotel.com">info@si-hotel.com</a> and mention the discount code "ICN17".
  attention: Please note that the Berlin Marathon will take place on September 24, which may lead to higher rates for September 23.
  reservation-link: mailto:info@si-hotel.com
  amenities: [Free WiFi, Free breakfast buffet]
  rates: [80 EUR single, 105 EUR twin or double room]
  deadline: July 24, 2017
  rating: 4
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d9724.780218003338!2d13.29915473918152!3d52.45749482525133!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e3!4m5!1s0x47a85a85dcb704d9%3A0xbb313ed96f89dbfb!2sHotel+Steglitz+International%2C+Albrechtstra%C3%9Fe+2%2C+12165+Berlin%2C+Germany!3m2!1d52.4564933!2d13.3213095!4m5!1s0x47a85a6f8915d465%3A0x3da1e59277049589!2sFreie+Universit%C3%A4t+Berlin+-+Institut+f%C3%BCr+Informatik%2C+Takustra%C3%9Fe+9%2C+14195+Berlin%2C+Germany!3m2!1d52.455889199999994!2d13.2972013!5e0!3m2!1sen!2sde!4v1499873865478"
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
  rating: 4
  deadline: The hotel has only very few rooms available.
  map: "https://www.google.com/maps/embed?pb=!1m28!1m12!1m3!1d1215.6352030609073!2d13.294112276154346!3d52.456130094925776!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!4m13!3e2!4m5!1s0x47a85a6e3c087b7b%3A0xbb7374dc78069e69!2sSeminaris+CampusHotel+Berlin%2C+Takustra%C3%9Fe+39%2C+14195+Berlin%2C+Germany!3m2!1d52.4571569!2d13.29389!4m5!1s0x47a85a6f8915d465%3A0x3da1e59277049589!2sFreie+Universit%C3%A4t+Berlin+-+Institut+f%C3%BCr+Informatik%2C+Takustra%C3%9Fe+9%2C+14195+Berlin%2C+Germany!3m2!1d52.455889199999994!2d13.2972013!5e0!3m2!1sen!2sde!4v1499873950304"

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
