# The Sensor Node Project #

The Sensor Node Project will provide a remote sensing capability for monitoring key parameters around the house.  My main reason for this project is to monitor our water tank level, usage and provide alarms to indicate too low or too high levels.  Currently, the Sensor Node architecture consists of three components:
  * The sensor node where the measurements are taken, stored temporarily and forwarded tot he sensor host when the time is right.
  * The sensor host is a _server_ that waits for remote sensor nodes to report their measurements, display data on a small LCD and allow data to be loaded to a PC/laptop.
  * Win32 software which captures data on the host PC/laptop.  Currently, this will be developed on Windows using Python.

The current plan is to base all hardware on the ATmega8 and nRF24L01+.

# Status #

The project is being established and this is still early days.  I have tested the concept using Arduino and STM32 based boards and everything seems feasible.   Below is a table that lists key milestones and their status.

| Stage | Date | Status |
|:------|:-----|:-------|
| Investigation | Sep 2011 | Completed. |
| Sensor Node Hardware | Oct 2011 | Completed and tested. |
| Software development | Nov 2011 | Started |
| Test  | Nov - Dec 2011 | Not started |
| Implement | Dec/Jan 2011 | Not started |