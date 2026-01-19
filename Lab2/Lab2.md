# LAB 2: NETWORK COMMAND FOR TESTING AND TERMINOLOGY

## OBJECTIVE
- To understand the purpose of common network commands used for testing and troubleshooting.  
- To learn the syntax and usage of essential network diagnostic commands.  
- To analyze network connectivity and identify communication issues.

## REQUIRED COMPONENTS
- A computer with Command Line Interface (CLI) access  
- Network connection (wired or wireless)

## THEORY

### Network Commands
Network commands are essential tools used to test, monitor, and troubleshoot network connectivity and performance issues. These commands allow users and network administrators to check whether devices are properly connected to a network, verify IP configuration details, and identify problems such as packet loss, incorrect routing, or DNS resolution failures.

Network configuration commands such as `ipconfig/ifconfig`, `route print`, and `getmac` display essential details including IP address, subnet mask, default gateway, routing table, and MAC addresses of network interfaces. These details are crucial for verifying correct network setup and diagnosing configuration-related problems.

Overall, understanding these network commands is important for effective network troubleshooting, ensuring reliable communication, and maintaining proper network performance.

## SYNTAX AND USAGE OF COMMON NETWORK COMMANDS

### 1) ping
- **Syntax:** `ping [hostname or IP address]`  
- **Usage:** Tests the reachability of a host on an IP network and measures the round-trip time.

### 2) ipconfig (Windows) / ifconfig (Linux)
- **Syntax:** `ipconfig` or `ifconfig`  
- **Usage:** Displays current TCP/IP network configuration values.

### 3) tracert (Windows) / traceroute (Linux)
- **Syntax:** `tracert [hostname or IP address]` or `traceroute [hostname or IP address]`  
- **Usage:** Determines the route taken by packets to reach a host.

### 4) netstat
- **Syntax:** `netstat -a` or `netstat -n`  
- **Usage:** Displays active TCP connections and listening ports.

### 5) nslookup
- **Syntax:** `nslookup [hostname]`  
- **Usage:** Queries DNS to obtain domain name or IP address mapping.

### 6) arp
- **Syntax:** `arp -a`  
- **Usage:** Displays the ARP table.

### 7) telnet
- **Syntax:** `telnet [hostname or IP address] [port]`  
- **Usage:** Tests connectivity to a specific port.

### 8) getmac
- **Syntax:** `getmac`  
- **Usage:** Displays MAC addresses of network adapters.

### 9) netsh wlan (Windows)
- **Syntax:** `netsh wlan show profiles`  
- **Usage:** Manages wireless network profiles.

### 10) route print
- **Syntax:** `route print`  
- **Usage:** Displays the IP routing table.

### 11) nbtstat
- **Syntax:** `nbtstat -a [hostname]`  
- **Usage:** Displays NetBIOS over TCP/IP statistics.

### 12) whois
- **Syntax:** `whois [domain name]`  
- **Usage:** Retrieves domain registration information.

## PROCEDURE
- Open the Command Line Interface (CLI).  
- Execute `ipconfig` or `ifconfig` to view network configuration.  
- Run the remaining commands listed above.  
- Observe and record the outputs.

## OUTPUT
The outputs of all executed commands are attached separately along with
their respective syntax and usage descriptions. Some commands did not
display output due to installation or recognition issues.

## CONCLUSION
This lab successfully introduced various network commands used for testing
and troubleshooting network connectivity issues. By using these commands, important information about network configuration, connectivity status, routing paths, and DNS resolution was obtained. The practical use of
commands such as ping, ipconfig, tracert, and netstat helped in
understanding how network problems can be identified and analyzed. Overall, this lab enhanced practical knowledge of network troubleshooting
techniques and highlighted the importance of command-line tools in
maintaining reliable and efficient network communication.
