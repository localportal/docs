---
description: Smart Routing
---
Localportal enhances network efficiency and reliability by leveraging a global network of edge servers for smart routing. This system ensures that traffic is routed through the edge server closest to the user's location, optimizing both speed and response times. Upon executing the connection command, Localportal identifies and connects your machine to the nearest edge server based on real-time geographic data. This process involves automated configuration of the necessary interface and DNS settings, directing your machine's traffic through the optimal server. Unlike the majority of reverse tunneling based products/services available, Localportal is among the few services that implement this type of intelligent edge server routing. This capability provides a significant advantage in performance and reliability, catering specifically to developers seeking robust and efficient networking solutions.

## Initial Connection Process

Edge Server Detection: The system determines the closest edge server from your current location when the localportal link command is executed.
Configuration: Automatically configures the interface and DNS to route through the identified edge server.

**Example**: If you are in New York and execute the localportal link my-laptop, the system will choose an edge server located in New York (named namora) as the most efficient routing point.

## Limitations and Workarounds

Once connected, your machine's routing configuration becomes static, associating it with the initially selected edge server. This setup does not automatically update based on subsequent location changes. For instance, if you travel from New York to London, your traffic will continue to route through the New York server, despite London having a closer and more efficient server (named hagrid).

**Reassigning Edge Servers**: To connect to a different edge server, closer to your new location, follow these steps:

- Remove Existing Configuration: Delete your machine's interface configuration from the dashboard.
- Reconnect: Use the localportal link command again from your new location to initiate the smart routing through the nearest edge server.

This process ensures that you are always connected to the most optimal server as per your current geographic location.
