# peel-waste-collection
Peel Waste Collection Schedules in Digital Format.  Scraped and reverse engineered from the website. 😅️

## Collection Overview

### Schedules
There are two main collection schedules: Brampton/Mississauga and Caledon.  These are further broken down as shown below.

Schedule | Days | Zones | # Schedules
-------- | ---- | ----- | -----------
Brampton & Mississauga | Monday-Thursday | A & B | 8
Caledon Urban | Monday-Tuesday | A & B | 4
Caledon Rural | Monday-Tuesday | A & B | 4

Brampton and Mississauga have collection days covering Monday to Thursday with A & B subzones.  Caledon has collections on Monday and Tuesday with A & B subzones; however, it is further subdivided within these zones to include urban and rural collection schedules.  Urban collection zones have more frequent collection of some types of waste, such as yard waste.  These are generally the rural service centres, major hamlets, and areas with suburban style housing tracts.

A list of the various collection schedules can be found in the Calendar-Index.csv file.

### Collection Zones
The Region releases collection zones on their open data website; however, one glaring omission is that Caledon does not have urban/rural areas split, effecting the acccuracy of the information that can be provided to clients.  The open data waste collection schedule was downloaded, projected to WGS84, and modified to break apart urban and rural areas.  This was done using the search function to find which addresses fall within each collection zone.

## General Collection Information
* Organics is picked up weekly, every week of the year.
* Garbage **or** recycling are picked up weekly.
* Yard waste (Mississauga & Brampton) pick-up is weekly starting in March, then becomes bi-weekly for a period in July-August (ish), then becomes weekly until mid-December.  Caledon urban areas have pick-up every other week and Caledon rural have some pick-ups in the spring and fall that fall on Fridays.
* Tree pick-up once a year - i.e. Christmas tree.
* Two to three garbage exemption pick-ups per year, depending on the sub-zone and when collection takes place.
* Two battery pick-ups per year.

## License
The data found in this repository has been released into the Public Domain through the Creative Commons 0 License.  See the LICENSE file for full rights and limitations.  Zone polygons were released under the Region's open data license, which allows for modification and commercial use.
