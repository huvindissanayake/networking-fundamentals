# Connecting an IoT Webcam to a Wireless Router Using Cisco Packet Tracer

## 1. Objective

To connect an IoT webcam to a wireless home router using Cisco Packet Tracer and understand how wireless network identification (SSID) affects device connectivity.

## 2. Network Topology

The simulated network consists of:

- HomeRouter-PT-AC (Wireless Router)
- Laptop-PT
- PC-PT
- Webcam (IoT Device)

The laptop and webcam connect wirelessly to the home router, while the PC uses a wired connection.

## 3. Initial Problem

The webcam did not connect to the wireless router using the initial connection attempt.

## 4. Investigation and Solution

Upon inspecting the webcam's wireless configuration, I found that its SSID did not match the SSID configured on the home router.

The router's SSID was `Default`.

I modified the webcam's wireless configuration and changed its SSID to `Default` to match the router.

After applying the configuration, the webcam successfully connected to the wireless network.

## 5. Key Concepts Learned

- **SSID (Service Set Identifier):** The name used to identify a wireless network.
- **Wireless Connectivity:** Wireless devices must use compatible wireless network settings to establish a connection.
- **Device Configuration:** Wireless network settings can be configured on individual devices.
- **IoT Networking:** IoT devices such as webcams can communicate through wireless network infrastructure.

## 6. Results

The webcam successfully established a wireless connection with the home router after its SSID configuration was corrected.

## 7. Evidence

See `topology.jpg` for the Packet Tracer network topology.

The original Packet Tracer project is available in `Network.0.pkt`.

## 8. Further Exploration

- Investigate wireless authentication and encryption.
- Explore how WPA2 security settings affect wireless connectivity.
- Test the webcam's connectivity and communication with other devices.
- Investigate IP address assignment through DHCP.
