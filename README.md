[![Mini Project](https://cdn2.iconfinder.com/data/icons/circle-icons-1/64/lightbulb-24.png)  **MINI PROJECT**](https://ameenkb.github.io/#mini-project)

#### MINI PROJECT
**SOLAR MPPT AND CHARGE CONTROLLER USING ARDUINO**

* **Introduction to MPPT**

Maximum power point tracking (MPPT or sometimes just PPT) is a technique used commonly with wind turbines and photovoltaic (PV) solar systems to maximize power extraction under all conditions.

Although solar power is mainly covered, the principle applies generally to sources with variable power: for example, optical power transmission and thermophotovoltaics.

![Solar Panel](http://geco.coop/wp-content/themes/geco-coop/img/about-bg.png)

PV solar systems exist in many different configurations with regard to their relationship to inverter systems, external grids, battery banks, or other electrical loads. Regardless of the ultimate destination of the solar power, though, the central problem addressed by MPPT is that the efficiency of power transfer from the solar cell depends on both the amount of sunlight falling on the solar panels and the electrical characteristics of the load. As the amount of sunlight varies, the load characteristic that gives the highest power transfer efficiency changes, so that the efficiency of the system is optimized when the load characteristic changes to keep the power transfer at highest efficiency. This load characteristic is called the maximum power point and MPPT is the process of finding this point and keeping the load characteristic there. Electrical circuits can be designed to present arbitrary loads to the photovoltaic cells and then convert the voltage, current, or frequency to suit other devices or systems, and MPPT solves the problem of choosing the best load to be presented to the cells in order to get the most usable power out.

* **Introdution to Arduino**

Arduino is an open source computer hardware and software company, project, and user community that designs and manufactures single-board microcontrollers and microcontroller kits for building digital devices and interactive objects that can sense and control objects in the physical world. The project's products are distributed as open-source hardware and software, which are licensed under the GNU Lesser General Public License (LGPL) or the GNU General Public License (GPL), permitting the manufacture of Arduino boards and software distribution by anyone. Arduino boards are available commercially in preassembled form, or as do-it-yourself kits.

![Arduino](https://www.arduino.cc/en/uploads/Trademark/ArduinoCommunityLogo.png)

Arduino board designs use a variety of microprocessors and controllers. The boards are equipped with sets of digital and analog input/output (I/O) pins that may be interfaced to various expansion boards (shields) and other circuits. The boards feature serial communications interfaces, including Universal Serial Bus (USB) on some models, which are also used for loading programs from personal computers. The microcontrollers are typically programmed using a dialect of features from the programming languages C and C++. In addition to using traditional compiler toolchains, the Arduino project provides an integrated development environment (IDE) based on the Processing language project.

* **Working Principle**

The Maximum Power Tracker uses an iterative approach to finding this constantly changing MPP. This iterative method is called Perterb and Observe or hill climbing algorithm.To achieve MPPT, the controller adjusts the voltage by a small amount from the solar panel and measures power, if the power increases, further adjustments in the direction are tried until power no longer increases.

The voltage to the solar panel is increased initially, if the output power increase, the voltage is continually increased until the output power starts decreasing. Once the output power starts decreasing, the voltage to the solar panel decreased until maximum power is reached. This process is continued until the MPPT is attained. This result is an oscillation of the output power around the MPP.

[![Back](https://cdn0.iconfinder.com/data/icons/navigation-set-arrows-part-one/32/DoubleChevronUp-20.png) BACK TO TOP ![Arrow](https://cdn0.iconfinder.com/data/icons/navigation-set-arrows-part-one/32/DoubleChevronUp-20.png)](https://ameenkb.github.io/#contents)
  
![Break](https://raw.githubusercontent.com/ameenkb/ameenkb.github.io/master/Images/Blank.png)

