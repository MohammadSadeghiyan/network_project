# network_project

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Project Components](#project-components)
  - [EIGRP Protocol](#eigrp-protocol)
  - [OSPF Protocol](#ospf-protocol)
  - [HSRP Protocol](#hsrp-protocol)
  - [Routing Redistribution](#routing-redistribution)
  - [Server Configurations in Packet Tracer](#server-configurations-in-packet-tracer)
  - [Wireless Router Configurations](#wireless-router-configurations)
- [How to Set Up the Project](#how-to-set-up-the-project)
- [Testing and Verification](#testing-and-verification)
- [License](#license)

## Project Overview
This project is a network simulation implemented using Cisco Packet Tracer. It covers various networking protocols and configurations, including dynamic routing, failover mechanisms, and server configurations.

## Objectives
- Implement Enhanced Interior Gateway Routing Protocol (EIGRP) for efficient routing.
- Implement Open Shortest Path First (OSPF) for inter-area routing.
- Configure Hot Standby Router Protocol (HSRP) for high availability.
- Utilize Routing Redistribution for interoperability between different routing protocols.
- Set up DHCP, DNS, Web, and Mail servers in Packet Tracer.
- Configure wireless routers for seamless network connectivity.

## Technologies Used
- **Cisco Packet Tracer** for network simulation.
- **EIGRP** as a dynamic routing protocol.
- **OSPF** for scalable and efficient routing.
- **HSRP** for redundancy and failover.
- **Various network services** including DHCP, DNS, Mail, and Web services.

## Project Components

### EIGRP Protocol
- Implemented as a primary routing protocol.
- Supports fast convergence and efficient routing.
- Configured with appropriate AS numbers and neighbor relationships.

### OSPF Protocol
- Used for hierarchical and scalable routing.
- Configured with multiple areas for optimized routing.
- Uses link-state advertisements for fast convergence.

### HSRP Protocol
- Provides redundancy for gateway routers.
- Ensures automatic failover in case of router failure.
- Configured with primary and standby routers.

### Routing Redistribution
- Enables communication between different routing domains.
- Configured to share routes between EIGRP, OSPF, and other protocols.
- Uses administrative distance adjustments for optimal routing.

### Server Configurations in Packet Tracer
- **DHCP Server**: Assigns dynamic IP addresses to network clients.
- **DNS Server**: Resolves domain names to IP addresses.
- **Mail Server**: Handles email communication.
- **Web Server**: Hosts web-based applications.

### Wireless Router Configurations
- Configured to provide wireless connectivity.
- Implements security measures such as WPA2 encryption.
- Ensures seamless integration with wired infrastructure.

## How to Set Up the Project
1. Open Cisco Packet Tracer and load the provided `.pkt` file.
2. Verify that all routers, switches, and hosts are correctly connected.
3. Configure EIGRP, OSPF, and HSRP as per the provided settings.
4. Set up DHCP, DNS, Web, and Mail servers.
5. Test connectivity between wired and wireless clients.

## Testing and Verification
- Use `ping` to test connectivity between devices.
- Use `show ip route` to verify routing tables.
- Use `show standby` to confirm HSRP status.
- Use `show ospf neighbor` to verify OSPF adjacencies.
- Access the web server via a browser to test HTTP services.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

