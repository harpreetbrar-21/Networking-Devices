# Networking Devices --- Beginner's Guide

A concise study resource based on my first CCNA networking lesson.

## What Is a Network?

A computer network connects devices so they can communicate and share
resources.

A **node** is a device connected to a network. Clients and servers are
also called **end hosts** or **endpoints**.

## Common Network Nodes

### Client

A client is a device that requests or accesses a service from a server.

**Examples:** A computer watching a YouTube video or a phone requesting
a file through AirDrop.

### Server

A server is a device that provides services or resources to clients. The
same device can act as a client in one situation and a server in
another.

### Switch

A switch connects end devices, such as PCs and servers, within the same
local area network (LAN). It forwards traffic within that LAN and
usually has many ports for connecting devices.

### Router

A router forwards traffic between different networks. It can connect
separate LANs and help route traffic toward the Internet. Routers
generally have fewer interfaces than switches.

### Firewall

A firewall monitors and controls network traffic according to configured
security rules. Rules determine which traffic is allowed or blocked.

-   **Network firewall:** A hardware device that filters traffic between
    networks.
-   **Host-based firewall:** Software that filters traffic entering and
    leaving an individual device.
-   **Next-generation firewall:** A firewall with more advanced
    filtering capabilities.

## Quick Comparison

  Node or device   Main role
  ---------------- --------------------------------------------------
  Client           Requests a service
  Server           Provides a service
  Switch           Connects devices within a LAN
  Router           Forwards traffic between networks
  Firewall         Allows or blocks traffic based on security rules

## How They Work Together

In a simple enterprise network, PCs and servers connect to switches.
Routers connect separate networks, while firewalls help protect the
network by filtering traffic. When a client requests a file or webpage,
a server provides the requested service.

A network diagram may use a cloud to represent the Internet when the
internal details of the Internet are not important to the diagram.

## Packet Tracer Lab Notes

> Fill in this section with details from the lab you actually completed.
> Do not claim a test succeeded unless you verified it.

-   **Objective:** Practise identifying network devices and how they
    connect.
-   **Devices used:** Add the devices from your actual topology.
-   **Topology screenshot:** Add your screenshot in the repository and
    link it here.
-   **Steps completed:** Record the steps you followed.
-   **Tests performed:** Record any connectivity tests you actually ran.
-   **Observed results:** Write what happened.
-   **What I learned:** Summarize your own takeaways.

Example image link (update the path and filename to match your
repository):

`![Packet Tracer topology](../diagrams/networking-devices-topology.png)`

## Quick Quiz

**1. Which device is appropriate for connecting 30 PCs within the same
LAN?**

A. Router\
B. Firewall\
C. Switch\
D. Server

**2. A friend's phone sends you a video through AirDrop. What role is
the friend's phone playing in that transaction?**

A. Server\
B. Client\
C. LAN

**3. While watching a YouTube video, what role is your computer or phone
playing?**

A. Server\
B. End host\
C. Client

**4. Which device is designed to forward traffic between separate
networks?**

A. Firewall\
B. Host\
C. LAN\
D. Router

**5. What type of firewall offers more advanced filtering
capabilities?**

A. Host-based firewall\
B. Next-level firewall\
C. Next-generation firewall\
D. Top-layer firewall

### Answers

1.  **C --- Switch.** It connects many end devices within the same LAN.
2.  **A --- Server.** The phone provides the requested video.
3.  **C --- Client.** Your device requests and receives the video
    service.
4.  **D --- Router.** It forwards traffic between networks.
5.  **C --- Next-generation firewall.** It offers more advanced
    filtering capabilities.

## Key Takeaways

-   A client requests a service; a server provides it.
-   A switch connects devices within a LAN.
-   A router forwards traffic between networks.
-   A firewall filters traffic using security rules.
-   A device's role as client or server depends on the specific
    transaction.

## References

-   Jeremy's IT Lab --- CCNA course, introductory lesson on network
    devices.
-   Add the original lesson URL here.
