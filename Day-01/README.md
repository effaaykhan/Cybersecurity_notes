# Introduction to Cybersecurity
  - Cybersecurity is the practice of protecting computer systems, networks, and data from unauthorized access, theft, damage, or disruption. It involves the use of various technologies, procedures, and policies to protect against cyber threats.

  Some key aspects of cybersecurity include:
  
  1. Data Encryption: Encrypting sensitive data to protect it from unauthorized access.
  
  2. Firewalls and Network Security: Implementing firewalls and network security measures to monitor and control incoming and outgoing network traffic.
  
  3. Antivirus and Malware Protection: Using antivirus software and employing best practices to detect and remove malware from systems.
  
  4. Secure Coding Practices: Following secure coding practices and guidelines to develop secure software applications.
  
  5. User Authentication and Access Control: Implementing user authentication mechanisms and enforcing access control policies to protect user accounts and data.
  
  6. Secure Communication: Using secure communication channels (e.g., HTTPS) to protect data transmitted over the internet.
  
  7. Secure Cloud Computing: Utilizing cloud computing services securely, following best practices for data encryption, access control, and network security.
  
  8. Security Awareness and Training: Educating users about cybersecurity threats and best practices to protect themselves and their organizations.

# Fundamentals
  - At the beginning we need to setup an environment which requires some software that are given below:
    1. Virtual Box
         For Windows: [virtualbox.org](https://download.virtualbox.org/virtualbox/7.0.18/VirtualBox-7.0.18-162988-Win.exe)
         For Mac: [virtualbox.org](https://download.virtualbox.org/virtualbox/7.0.18/VirtualBox-7.0.18-162988-OSX.dmg)
    2. Kali Linux ISO file
         - For Virtual Box: [kali.org](https://cdimage.kali.org/kali-2024.2/kali-linux-2024.2-virtualbox-amd64.7z)
         - For VMware: [kali.org](https://cdimage.kali.org/kali-2024.2/kali-linux-2024.2-vmware-amd64.7z)
      
# Networking Fundamentals
## Network Address Translation (NAT)
  - Network Address Translation (NAT) is a method used in networking that allows one IP address to be mapped to another by modifying network address information in the IP header of packets while they are in transit across a traffic routing device. This technique enables multiple devices on a local network to use a single public IP address to access the internet, which conserves the number of public IP addresses an organization or ISP must use. It also adds a layer of security by masking internal IP addresses.

## Address Resolution Protocol (ARP)
  - ARP stands for Address Resolution Protocol. It's a network protocol used to find the hardware (MAC) address of a host from its known IP address. It is used when a device wants to communicate with another device on a local network and needs to resolve the IP address to a MAC address.

## Internet Protocol Address (IP Address)
  -An IP address (Internet Protocol address) is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol 
   for communication. It serves as an identifier for the device's location on the network.

  IP addresses are used to identify and route data packets between devices on different networks. They are typically represented in dot-decimal notation, such as 
  `192.168.1.1`, where each number represents one byte (8 bits) of information.
  
  IP addresses are divided into two categories:
  
   1. Public IP addresses: These are assigned to devices that are directly connected to the Internet. They are used to identify and locate devices on the 
       public Internet.
  
   2. Private IP addresses: These are assigned to devices within a private network (e.g., a home network or an office network) that is not directly connected            to the public Internet. Private IP addresses are used for internal communication within the network.
  
  IP addresses are essential for communication between devices on different networks and for routing data packets to their intended destinations. They are 
  managed by Internet Service Providers (ISPs) and Network Information Centers (NICs).

  ## Media Access Control Address (MAC Address)
   - A MAC address (Media Access Control address) is a unique identifier assigned to network interfaces of devices for communication on a local area network (LAN). It serves as a physical address and helps devices communicate with each other over a network.

  MAC addresses are 48-bit (6-byte) numbers that are permanently assigned to network interfaces by the manufacturer. They are represented in hexadecimal notation,   with each byte separated by a colon (:) or hyphen (-).
  
  MAC addresses are used for:
  
  1. Address Resolution Protocol (ARP): When a device wants to communicate with another device on the same network, it uses its MAC address to resolve the         
     corresponding IP address.
  
  2. Networking: Devices use MAC addresses to identify each other and to filter and control network traffic.
  
  3. Security: MAC addresses can be used for access control and network security measures.
  
  MAC addresses are typically displayed on network interface cards (NICs) and are fixed for the lifetime of the device. They are managed by the IEEE (Institute of 
  Electrical and Electronics Engineers) and are assigned by the manufacturer.


