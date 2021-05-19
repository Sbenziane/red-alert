# Description

API Class to get data about rockets flying from Gaza strip to Israel.
the API use's the official public API provided by "Pikud ha-oref" in Israel.

# Features

* Get red-alerts in real-time from "Pikud ha-oref" public API

* Fetch location data from alerts codes (coordinates, city names, time to run for shelters)

* Generate random coordinates within a city for visualization of a flying rocket

* Count number of alerts currently there is

# FAQ

### Q) Why is this even helpful?

*    The Class I made is helpful for developers and makers as one
     Who are willing to develop platforms / apps based on Israeli "Pikud ha-oref" system.
     The class provides the necessary functions and tools to get the latest information
     About the Israeli missiles status and when Israel is under attack.

### Q) Can't the enemy use it against Israel?

*    No. All the information in the Class is public and available,
     All I did is to organize it at one place for easy access.
     I also scraped and organized the cities names with their area codes for easy reading.

### Q) Can I take the code and make a product of my own using your Class?

*    Absolutely. The code and everything inside the repository is open-sourced.
     The Code is under MIT license - please make sure to understand the meaning.
     The Code provided AS IS WITHOUT ANY WARRANTY.

### Q) How can I visualize how much time the rocket have till it will hit the city?

*    Use the milliseconds calculated from how much time left for people to run to shelters,
     Then visualize using that seconds of long the rocket has to fly till it will hit the city.
     
### Q) Is it possible to predict or to know where exactly the missile will land?

*    No, at least not for the developers. the military may have such capabilities.
     The prediction is not possible due to many parameters such as:
     Where the rocket came from, How much fuel is inside the rocket, at what speed is the rocket flying,
     Directions of the rocket and weather conditions - something which make it impossible for any
     non-military individual, even with technology such as machine learning and prediction algorithms.

# Requirements

* Python requests library
```sh
$ pip install requests
```
* NodeJS request library
```sh
$ npm install request
```

https://web.archive.org/web/20140824082430/http://37.187.218.147/
