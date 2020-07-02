What is the Server Discovery?
Server Discovery is a Java Network Simulator for ad-hoc and disributed and point-to-point message networks. 
With Server Discovery you can create simulators easily just by clicking on a GUI. 
Each node represents a server instance. Each server then boardcasts a broadcaster message in the open air repeately when created. 
Every node in the simulator has a range defined that describes reachability of it, like an physical antenna. These are all can be configured in the simulator easily.
In order for each node to be reachable by other nodes new routing table is created dynamically as nodes move, remove or created in the environment. 
Meanwhile the whole node in the simulator synchronously broadcasts at the same time with the latest shortest path table. 
This table helps like a map of how to reach to each node in the system. Regular text messages then can be passed to other nodes crossing each node until reach to destination.

Watch video for more information.

[![Watch the video](screenshot.png)](https://github.com/metao1/server-discovery/raw/master/video.gif)
[![Watch the video](screenshot.png)](https://www.youtube.com/watch?v=GeJ2hzihFaM)
