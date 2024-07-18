<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![Portfolio][portfolio-shield]][portfolio-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">

  <h3 align="center">Density Based Traffic System</h3>

  <p align="center">
A density based dynamic Traffic control  system where the timing of signals will change automatically on sensing the traffic density at any junction!!    <br />
    <a href="https://github.com/Anshullanjewar/Density-based-Traffic-System"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center" float="left">
<table>
  <tr>
    <td><img src="https://github.com/Anshullanjewar/Density-based-Traffic-System/blob/main/Traffic%20System%20(1).png" width="1080"></td>
    <td><img src="https://github.com/Anshullanjewar/Density-based-Traffic-System/blob/main/Traffic%20System%20(2).png" width="1080"></td>
  </tr>
 </table>

This project is aimed at designing a density based dynamic Traffic control  system where the timing of signals will change automatically on sensing the traffic density at any junction. Traffic congestion is a severe problem in most cities across the world and therefore it is time to shift more manual mode or fixed timer mode to an automated system with decision-making capabilities

PRESENT TRAFFIC SIGNAL SYSTEM
Despite many advances in today’s digital hegemony, traffic management remains a big problem in India. Manual traffic control systems are still in use in some regions of India. A comparable and matching education program is required by the driver-licensing authority. To ensure that those who operate motor vehicles understand the rules of the road as well as the precautions that are required or prescribed when a particular control system is in use. Each traffic control device is governed by standards of design and usage


### PROPOSED METHOD
The model works on the principle of changing the delay of traffic signals based on the numbers of cars passing through an assigned section of the road. There are four sensors placed on four sides of a four-way road which count the number of cars passing by the area covered by the sensors.

<table>
  <tr>
    <td><img src="https://github.com/Anshullanjewar/Density-based-Traffic-System/blob/main/Traffic%20System%20(1).png" width="1080" height="500"></td>
  </tr>
 </table>


Here we are using IR sensors to replace traffic control systems to design an intelligent traffic control system. IR sensor contains an IR transmitter  IR receiver (photodiode) in itself. This infrared transmitter and receivers will be positioned at a specific distance apart on opposite sides of lanes. The infrared sensor as the vehicle passes through IR sensors, proceeding with the international conference on inventive computing and Informatics will trace it and send data to the microcontroller. Based on the density of vehicles, the  microcontroller can count the number of vehicles and provide the LEDS with a glowing time. If the density of a lane or route is greater, the LED will shine for a longer period than normal, and vice versa. The traffic lights are initially running at a fixed delay of 5 seconds, which in turn produces a delay of 20 seconds in the entire process. This entire embedded system is placed at the junction. Microcontroller is interfaced with LEDs and the IR sensors required are 4 and Led’s 12. Therefore these are connected to any two ports of the microcontroller. When a sensor detects a moving object, the comparator output drops to zero; otherwise, it is high, such as +5v or 3.3v. If the detector‘s state differs significantly from the previous day, that clause is met, and the statement in parenthesis is terminated. However, the detector switches back and forth from high to low.


<table>
  <tr>
    <td><img src="https://github.com/Anshullanjewar/Density-based-Traffic-System/blob/main/Traffic%20System%20(2).png" width="1080" height="500"></td>
  </tr>
 </table>

 
### Hardware Integrated

* Power Supply
* Arduino ATmega328
* IR Sensor
* 7-Segment Display
* Voltage Regulator LM7805 IC
* Transformer 230V to 2V 3A
  

### WORKING 
The model works on the principle of changing the delay of Traffic signals based on the density of               vehicles passing through the assigned section of the road. There are four sensors placed on  four sides of a four-way road, which sense the density of vehicles passing by the area covered by the sensors. Here we are using IR sensors to design an intelligent traffic control system. These IR sensors will be mounted on the same sides of the road at a particular distance. As the vehicle passes these IR sensors, the IR sensor will detect the vehicle & will send the information to the microcontroller. The microcontroller will sense the density of  vehicles and provide the glowing time to the LED as per the density of vehicles. The traffic lights are initially running at a fixed delay of 20 seconds, if any of the four IR sensors sense the density at that particular road is increasing then the timing of that particular road will be automatically shifted to 50 seconds.
If there is traffic at all signals, then the system will normally work by controlling the signals one by one. If there is no traffic at all of the 4 signals, then also the system will normally work by controlling the signals one by one.

### CONCLUSION 
There is an exigent need for an effective traffic management system in another country, as India meets with 384 road accidents every day. To reduce this congestion and unwanted tie delay tfour-wayn advanced senses are designed here in this project. With fid application of this technology, the maddening chaos of traffic can be effectively channelized by distributing the time slots based on the merit of the vehicle's load in the certain lane of multiple junction crossings. We have successfully implemented the prototype at the laboratory scale with remarkable outcomes. The next step forward is to implement this schema in real-life scenarios for first-hand results, before implementing it on a larger scale. We believe that this will bring a revolutionary change in the traffic management system sense application in an actual field environment.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Get Started!

To learn more about the project, explore the codebase, or contribute, visit the GitHub repository:

* **Project Link:** https://github.com/Anshullanjewar/Density-based-Traffic-System



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Name - [Anshul Lanjewar](https://www.linkedin.com/in/anshul-lanjewar) - anshullanjewar12@gmail.com

Project Link: [https://github.com/Anshullanjewar/Density-based-Traffic-System](https://github.com/Anshullanjewar/Density-based-Traffic-System)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Portfolio-shield]: https://img.shields.io/github/contributors/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[portfolio-url]: https://anshullanjewar.github.io/
[stars-shield]: https://img.shields.io/github/stars/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Anshullanjewar/Guided_App/issues
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Anshullanjewar/Guided_App/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]:https://github.com/Anshullanjewar/Guided_App/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/anshul-lanjewar
[Java_url]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[firebase_url]: https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34
[android_url]: https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white
