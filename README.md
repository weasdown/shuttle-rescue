# shuttle-rescue

GMAT simulation of a Space Shuttle rescue scenario.

## Problem

The below is copied (with code formatting added) from page 420 (PDF page 447) of _Fundamentals of Astrodynamics and Applications_, 4th ed., by David A. Vallado. The 5th edition is now current - please see [abebooks.co.uk] if purchasing from the UK or [microcosmpress.com/vallado] for elsewhere.

>_Hint: This problem mainly uses techniques from this chapter but ultimately requires a solution of the Lambert problem discussed in Chap. 7._
>
>You are working as a junior engineer for NASA. The U.S. has launched the Space Shuttle for a scientific mission. The orbital elements are: `a = 6563.3698 km`, `e = 0.004 806 0`, `i = 45.0°`, `Ω = 95.26 277 50°`, `ω = 50.375 078 0°`, `M = 0.0°` on the epoch of December 24, 1998, at 0h UT, `Julian date = 2,448,980.500`. The Russian space shuttle (Buran) is about to be launched and has two satellites on board: a tracking and relay satellite (Gorizont) and a new rescue module for their MIR space station (`a = 6727.7061 km`, `e = 0.000 744 4`, `i = 51.6598°`, `Ω = 159.7517°`, `ω = 117.6835°`, `M = 242.4909°` on the epoch of December 24, 1998, at 3:40:53.6148 UT). An unknown piece of debris hits and cripples the U.S.
Shuttle, threatening the lives of the astronauts. Your job is to determine how soon the experimental Russian module can retrieve the astronauts. Several restrictions apply:
>
><ol type="a">
> <li>We know the injection longitude of Buran to be 80.0° W, and the elapsed time from launch is 75.667 min for standard launches. This will place Buran at apogee on the initial revolution of a 0 km × 80 km orbit. In addition, Buran will be launched from Tyuratam, located at 46.0°N, 65.0°E. The orbit will be a standard circular orbit with `i = 51.6°`. The sequence to achieve orbit is: 1: (0 km × 80 km), 2: (80 × 364 km), 3: (364 × 364 km). Buran can remain in orbit for only two days after launch and can’t maneuver. It must launch on December 24.</li>
> <li>The Gorizont satellite will occupy a geostationary orbit at 43.5°E ±3° and must be on station before December 26, 1998, 12h UTC. The Gorizont satellite has a fixed Δv motor capable of 2819.4 m/s to start the combined Δv transfer to geosynchronous. Ninety minutes are required to check out the Gorizont immediately before deployment. The Gorizont satellite must use 0 to 6 phasing revolutions to minimize transfer time. We like to start the transfer orbit at the ascending node to allow tracking stations in the Northern Hemisphere to monitor the transfer. Any motor firing must be within sight of a U.S.ground station to enhance detection and initial orbit determination. The Gorizont satellite requires Sun acquisition for alignment at perigee motor firing. The Sun sensor’s cone of view has a width of 25° and can be configured to view from 45° to 135° off the satellite’s spin axis. The configuration is established before launch and can’t be changed in orbit. The satellite is deployed at the node before starting the transfer to allow the orbiter to obtain proper separation and avoid plume impingement. This deployment <i>should</i> occur in sight of a ground station but doesn’t have to.</li>
> <li>The rescue module uses the Gorizont tracking satellite for data; thus, the Gorizont must deploy first, and the module can’t leave Buran until Gorizont is in place at geosynchronous. The ten minutes from rescue-module removal to motor firing must occur in sight of the Sun and Gorizont. The rescue module’s perigee motor for the first transfer Δv can provide up to 3657.6 m/s; the apogee motor can produce 2600 m/s. Time of flight from the rescue-module deployment to rendezvous must not exceed 90 minutes because of limitedoxygen supplies (suggested minimum time is 30 min).</li>
></ol>

[abebooks.co.uk]: https://www.abebooks.co.uk/Fundamentals-Astrodynamics-Applications-5th-Edition-David/31476421520/bd
[microcosmpress.com/vallado]: https://microcosmpress.com/vallado/
