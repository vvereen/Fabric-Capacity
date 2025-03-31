# Fabric-Capacity
A collection of useful Fabric capacity assets.

## Capacity Scaling Example

6:00 – 8:00 am – F2

8:00 – 4:00 pm – F4 (Peak hours)

4:00 – 10:00 pm – F2

10:00 pm – 6:00 am – Paused

### Process

#### Capacity Scaling Logic App

•	Scale up to F4 between 8:00 am and 4:00 pm

•	Scale down to F2 at 4:00 pm

#### Capacity Pause/Resume Logic App

•	Pause at 10:00 pm

•	Resume at 6:00 am
