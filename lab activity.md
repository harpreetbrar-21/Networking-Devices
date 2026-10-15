# Packet Tracer Lab: Network Devices Setup

## Objective

Build a small enterprise network with two branches, routers, switches,
firewalls, end devices, and an Internet cloud. This activity focuses on
creating the topology; IP addressing and security rules can be
configured in later labs.

## Devices Required

-   Cisco 2911 routers --- 2
-   Cisco 2960 switches --- 2
-   Cisco ASA 5505 firewalls --- 2
-   PCs --- 2
-   Servers --- 2
-   Cloud/Internet symbol --- 1, if available

Device icons may differ slightly by Packet Tracer version. Use the
supplied screenshot as a layout reference.

## 1. Install Cisco Packet Tracer

1.  Visit Cisco Networking Academy or Skills for All, and sign in or
    create an account if prompted.
2.  Find the official Cisco Packet Tracer download page.
3.  Download the installer for your operating system.
4.  Open the installer and follow the installation steps.
5.  Launch Packet Tracer and sign in if requested.
6.  Select **File → New** to open a blank workspace.

Download Packet Tracer only from Cisco's official learning websites.

## 2. Add the Devices

Use the device categories in the bottom-left panel to place the
following: 1. Two **2911 routers** near the middle, one for each branch.
2. Two **2960 switches**, one on the left and one on the right. 3. Two
**ASA 5505 firewalls**, one on each side of the Internet. 4. Two **PCs**
near the left switch. 5. Two **servers** near the right switch. 6.
A **Cloud** device to represent the Internet, if available.

Arrange the devices neatly before connecting them.

## 3. Rename the Devices

Use the device display-name field to apply these suggested labels: -
Left PC: `Mark` - Second PC: `Henry` - Left switch: `SwitchEast` - Left
router: `Router1` - Left firewall: `ASA0` - Cloud: `THE INTERNET` -
Right router: `Router2` - Right firewall: `ASA1` - Right switch:
`SwitchWest` - Servers: `Max` and `Tyson` 

These labels help readability; they do not configure the devices.

## 4. Connect the Devices

1.  In the bottom connection toolbar, click the **lightning-bolt icon**
    labelled **Automatically Choose Connection Type**.
2.  Click the first device, then the second device to create a
    connection.
3.  Repeat for the remaining links.
4.  To keep the automatic connection tool active for multiple links,
    hold **Ctrl** while selecting the lightning-bolt icon, if supported
    by your Packet Tracer version. If it behaves differently, select the
    tool again for each link.
5.  If prompted to choose an interface, select an available suitable
    port.

### Suggested connection order

Build the main path from left to right: 1. `Mark` → `SwitchEast` 2.
`Henry` → `SwitchEast` 3. `SwitchEast` → `Router1` 4. `Router1` → `ASA0`
5. `ASA0` → `THE INTERNET` 6. `THE INTERNET` → `Router2` 7. `Router2` →
`ASA1` 8. `ASA1` → `SwitchWest` 9. `SwitchWest` → `Max` 10. `SwitchWest`
→ `Tyson` 

Packet Tracer may choose different cable types and interface numbers
automatically. Exact ports can vary.

## 5. Arrange and Save

1.  Move devices and labels so the diagram is easy to read.
2.  Keep the two branch LANs visually separate, with the Internet in the
    middle.
3.  Choose **File → Save As**.
4.  Save the project as `Networking-Devices-Setup.pkt`.
5.  Take a screenshot of the finished topology and save it as a PNG.

## 6. Check Your Work

-   [ ] All required devices are present.
-   [ ] Both PCs connect to the left switch.
-   [ ] Both servers connect to the right switch.
-   [ ] Routers and firewalls follow the reference layout.
-   [ ] The project is saved as a `.pkt` file.
-   [ ] A screenshot has been captured.

**Note:** Red link indicators can mean an interface or device is not
active yet. This activity focuses on building the diagram, so do not
claim end-to-end connectivity unless you configure the devices and test
it.

## Reference

Based on the introductory network-devices topology from Jeremy's IT Lab
CCNA course. https://youtu.be/H8W9oMNSuwo?si=yjVwhjop4_aRG4jM
