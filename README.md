# random_subway
 Generate random MTA subway routes

## What is this?

Can we generate random Subway routes?

## Resources / Where's this data from

MTA Developer Resources
https://www.mta.info/developers

General Transit Feed Specification [GTFS] Overview
https://gtfs.org/documentation/overview/

## Project Architecture

- Stop:
    - List of routes that run through it
    - Lat + Long
- Route:
    - a train route, that runs in both directions
    - Made up of Stops
- Time
    - If an when I start considering timing here, this will take care of that. See `stop_times.txt`

## Milestones

- Read in GTFS code and generate Stops + Routes
- Generate a random walk from a random stop
- Generate an intelligent walk / loop
- Visualization on a map to show where you're going
- Integrate train timings
