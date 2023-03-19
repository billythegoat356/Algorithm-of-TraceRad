# Algorithm-of-TraceRad
An incomplete algorithm who tries to precisely locate any IP adress.

# IMPORTANT
This program is incomplete because some factors cause it to not work, so it is still studied.
Please note that the following calculations may be incorrect or incomplete.
If you think it's the case, feel free to open an issue, while staying respectful.

# Theory
This algorithm will locate any IP by following these steps:
Execute 100 (or more) traceroutes and calculate the average ping between the last server and the IP.
Find another IP which has the same last server, but you need its exact adress.
Calculate its average ping with the server.
Establish a scale m/ms by dividing the distance between the server and the IP and the ping.
Multiply the ping of the first IP with the scale.
Trace a circle on a map where the center is the server, and the radius is the previous result.
The location of the IP will now logically be on the diameter of the circle.

# Problems
First of all, the ping is very unstable because it depends on the traffic of the server, the internet connection of the box, and more factors.
The distance isn't a straight line. To make a more advanced analyze, you should access the plans of the internet tunnels of your town and calculate the distance when using these lines.

# Contribute
If you have ideas to make this algorithm more advanced/precise, feel free to make a pull request.
You can also make an issue if you think the algorithm is wrong in any part.


# Authors
billythegoat356

