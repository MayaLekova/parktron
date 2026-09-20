# Introduction 

This repository contains the code for the simulation of parking spaces accompanying a PhD thesis on using Karma economies to improve utilisation of resources in an urban environment. Contributions are welcome, but please bear in mind that the main branch will be kept stable (as much as possible) with an up-to-date version of the simulation, as it is presented in the thesis.

# TODO

## Frontend

 - [ ] add time picker view for choosing a reservation start & duration
 - [ ] integrate [Leaflet module](https://nuxt.com/modules/leaflet)
 - [ ] add map view for picking a parking sub-zone

## Backend

 - [x] add a Nuxt skeleton app
 - [ ] implement an algorithm for conflict resolution on encounters of two drivers for the same parking slot

## Data store

 - [ ] add some storage (could be Postgres or MongoDB)
 - [ ] add GIS data

# Previous version of the prototype

## Data model

  - per-user data:

```
{
    urgency: String['low', 'medium', 'high'], 
    karma: Number,
    message: String
}
```

## References

 - [A blockchain-enabled parking space allocation...](https://www.sciencedirect.com/science/article/abs/pii/S0360835224007356)
 - [ ] TODO: some documentation for stability & popularity of NuxtJS
 - [ ] TODO: some docs for the performance of Leaflet
 - list of other [offline-first projects](https://openlocalfirst.org/schedules/)
