# HX711
This is an additional library for avr and can be modified for arduino, One can also use library of bodge HX711 library for HX711 interfacing with arduino only. This library however can interface with all avr platforms with just change in Makefile.
This is an advanced library which has been tested with 20kg load cell and can measure 1 gram minimum if proper change_rate setting is applied. If one want to use with arduino, one can use HX711.h and HX711.c files in arduino with SCK pin in arduino pin 5 and DT pin in arduino pin 6 and you are done.
It can also be used with other low cost load amplifiers like HX710A/B. It has been tested only on B. 

We are going to update the code with the new filter and drift correction soon as our research is complete.

I declare that this code is under GNU General Public License and acknowledge the contribution of millis.h and millis.c files taken from github and uart.h an uart.c taken from an unknown source.

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
