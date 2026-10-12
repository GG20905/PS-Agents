1. PEAS Framework: P - Performance measure, E- Environment,A- Actuators, S- Sensors

Performance Measure:
Does it get to it's end goal/location?
How fast does it get to its destination?
How safe was the overall trip? 
Does it follow the traffic laws and stipulations?
Using the shortest and most fuel efficient path?

Environment:
Partially observable: The agent does not have full information about the road and the state of the roads, which are dependent on factors like,hidden obstacles around corners, land changes and weather in different locations
Stochastic:The environment is unpredictable from the current state and action, unexpected events such as pedestrian crossing and dynamic weather.
Sequential: Current decision affects future decisions, such as overtaking means the agent will speed up.
Dynamic: The environmant can change while the agent decides its next move, e.g. Cars slowing down, pedestrian crossing, and others.
Single: The agent solely relies on itself to achieve its goal/ get to its destination

Actuators:
Steering wheel, brake system, and signaling devices

Sensors:
Cameras: Lane tracking and traffic light detection
GPS receiver: For navigation
Spehedometer: To measure vehicle speed and distance traveled

2. Directed graph and search tree



3. Nairobi to Kisumu Paths and Path cost function
Path A = 353 Km
Nairobi to Naivasha town: 91Km
Naivasha to Nakuru: 71 Km
Nakuru to Kericho: 107 Km
Kericho to Kisumu: 84 Km 

Path B = 356 Km
Nairobi to Narok: 143 Km
Narok to Bomet: 81 Km
Bomet to Sondu: 79 Km
Sondu to Kisumu: 53 Km


Calculate the cost of each path
Path A: Nairobi → Naivasha → Nakuru → Kericho → Kisumu
g(A)= 91+71+107+84 = 353 Km

Path B: Nairobi → Narok → Bomet → Sondu → Kisumu

g(B)= 143+81+79+53 = 356 Km

