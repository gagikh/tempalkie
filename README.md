A cool project using Dallas and talkie libraries
================================================

The project measures the temperature and ouputs to the speaker.

Usage
-----

This library supports the following devices:

    DS18B20
    DS18S20 - Please note there appears to be an issue with this series.
    DS1822

You will need a pull-up resistor of about 5 KOhm between the 1-Wire data line
and your 5V power. If you are using the DS18B20, ground pins 1 and 3. The
centre pin is the data line '1-wire'.

Speakers, 4-8KOhm speakers connectivity:

    Speaker 1-st pin - Digital ground
    Speaker 2-nd pin - Digital pin 3

In order to run the project, the following libraries should be checked-out into the arduino library:

    1. git clone https://github.com/milesburton/Arduino-Temperature-Control-Library.git
    2. git clone https://github.com/going-digital/Talkie.git
    3. git clone https://github.com/n0m1/Sleep_n0m1.git
    4. git clone https://github.com/pbrook/arduino-onewire.git

License
-------

This project is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public
License along with this library; if not, write to the Free Software
Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
