---
title: "GNSS-Free End-of-Row Detection and Headland Maneuvering for Orchard Navigation Using a Depth Camera"
collection: publications
permalink: /publication/2023-Machines-paper
excerpt: 'GPS-based navigation in orchards can be unstable because trees may block the GPS signal or introduce multipath errors. Most research on robot navigation without GPS has focused on guidance inside orchard rows; end-of-row detection has not received enough attention.'
date: 2023-01-09
paperurl: https://www.mdpi.com/2075-1702/11/1/84
citation: 
---
GPS-based navigation in orchards can be unstable because trees may block the GPS signal or introduce multipath errors. Most research on robot navigation without GPS has focused on guidance inside orchard rows; end-of-row detection has not received enough attention. Additionally, navigation between rows relies on reference maps or artificial landmarks. In this work, a novel row-end detection method is presented, which detects drastic changes in the statistical distribution of the sensed point cloud as the robot gets closer to the row’s end. A row-entry method was also implemented that builds a local map that is used by a reactive path tracker. The system was evaluated in a 24-row block in a vineyard. Once the robot was closer than 7 m from the end of a row, the algorithm detected it with a 100% success rate and calculated the distance from it with a mean error of 0.54 m. The system was also evaluated in vineyard configurations with parallel and slanted vine rows in consecutive blocks. The system worked well in all configurations, except where the next block had rows aligned to the rows of the current block and the headland width was closer than 5 m.

[Download paper here](https://www.mdpi.com/2075-1702/11/1/84)