# KALI LINUX TOOLS
  This repo contains the tools that are required for scanning networks, extracting credentials from any system or website and cracking the hashs.

  ## NMAP (Network Mapper)
  - Nmap (Network Mapper) is a powerful security scanning and network discovery tool used in Kali Linux. It allows you to scan networks, identify hosts, and discover services and operating systems running on them.
Here are some key features of Nmap:
1. Port Scanning: Nmap can scan for open ports on a target host or network. It can detect which ports are open, closed, or filtered.
2. Host Discovery: Nmap can discover hosts on a network by sending various types of packets and analyzing the responses.
3. Service and Version Detection: Nmap can identify the services running on the open ports and attempt to determine their versions.
4. OS Detection: Nmap can attempt to determine the operating system of the target host based on the responses to its scans.
5. Scripting Engine: Nmap supports a scripting engine that allows you to write and execute custom scripts to automate scanning and vulnerability assessment.

  - The latest version of this software as well as binary installers for Windows, macOS, and Linux (RPM) are available from [Nmap.org](https://nmap.org/download.html).
  - For full documentation refer this website [Nmap.org](https://nmap.org/docs.html).

  ### Installation
  - This is an in-built tool in kali linux simply type the command in your kali linux terminal
    ```bash
    nmap
    ```
  - If installation is required then simply go with the following command 
    ```bash
    sudo apt-get install nmap
    ```
  - For more in-depth compilation, installation and removal notes read the installation guide on [Nmap.org]( https://nmap.org/book/install.html)
  
  ### Usage
  


  ## Spiderfoot
   - SpiderFoot is an open-source intelligence (OSINT) automation tool that can be used in Kali Linux. It combines multiple OSINT modules to gather information about a target domain or IP address.

     ### Installation
        Here's how to install SpiderFoot in Kali Linux:
        
        1. Open the terminal and update the package list:
        ```bash
        sudo apt update
        ```
        2. Install SpiderFoot using pip:
        ```bash
        sudo apt-get install spiderfoot
        ```
        3. Verify the installation:
        ```bash
        spiderfoot -h
        ```
        This command should display the help message of SpiderFoot if the installation was successful.
        Once SpiderFoot is installed, you can use it to gather information about a target domain or IP address. Here's an example command to scan a domain:
        ```bash
        spiderfoot -t <target_domain>
        ```
        Replace `<target_domain>` with the domain you want to scan. This command will initiate a scan and gather various types of information about the target domain.
        SpiderFoot supports various modules that can be used to gather specific types of information, such as email addresses, subdomains, and more. You can explore the available modules and their options using the `-h` option or by reading the documentation.
        SpiderFoot is a valuable tool for OSINT and reconnaissance activities, as it automates the process of collecting information and helps identify potential targets or vulnerabilities.


  ## Gobuster
   - Gobuster is a tool used for brute-forcing URIs (directories and files), DNS subdomains, and virtual host names. It is a part of the Kali Linux distribution and can be easily installed using the package manager.
    Example:
  ```bash
  gobuster dir -u http://example.com -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt
  ```
  This command will scan the target URL `http://example.com` using the specified wordlist for directories and files.


  ### Installation
  Here's how to install Gobuster in Kali Linux:
  
  1. Open the terminal and update the package list:
  ```bash
  sudo apt update
  ```
  2. Install Gobuster:
  ```bash
  sudo apt install gobuster
  ```
  3. Verify the installation:
  ```bash
  gobuster -h
  ```
  This command should display the help message of Gobuster if the installation was successful.

  ### Usage
  
  Gobuster can be used to brute-force directories and files on a web server by providing a wordlist and target URL. Here's an example command to use Gobuster:
  ```bash
  gobuster dir -u <target_url> -w <wordlist_file>
  ```
  Replace `<target_url>` with the URL you want to scan and `<wordlist_file>` with the path to the wordlist file containing the directories and files to be brute-forced.
  Gobuster supports various options and can be customized to fit specific requirements. It is a powerful tool for web reconnaissance and can be used for targeted attacks or as part of a larger security assessment.

  
 



