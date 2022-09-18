<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147891038-00f57362-e843-4bfb-be31-606c954d4e6c.png">
  <br />
 WireGuard Guide
</h1>

#### A guide covering WireGuard including the applications, libraries and tools that will make you a better and more efficient  WireGuard development.

**Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/147891040-da2f6812-d0b0-40d4-a7a1-55d0080023fe.png">
  <br />
</p>


# Table of Contents

1. [Getting Started with WireGuard](https://github.com/mikeroyal/WireGuard-Guide#getting-started-with-wireguard)
     * [Tutorials](https://github.com/mikeroyal/WireGuard-Guide#tutorials)
     * [Books](https://github.com/mikeroyal/WireGuard-Guide#books)
     * [Podcasts](https://github.com/mikeroyal/WireGuard-Guide#podcasts)
     * [WireGuard Tools](https://github.com/mikeroyal/WireGuard-Guide#wireguard-tools)
     * [Setting up WireGuard with PiVPN](https://github.com/mikeroyal/WireGuard-Guide#setting-up-wireguard-with-pivpn)
     * [Setting up WireGuard on Unraid](https://github.com/mikeroyal/WireGuard-Guide#setting-up-wireguard-on-unraid)
     * [Setting up WireGuard on pfSense](https://github.com/mikeroyal/WireGuard-Guide#setting-up-wireguard-on-pfsense)
     * [Setting up WireGuard on OpenWRT](https://github.com/mikeroyal/WireGuard-Guide#setting-up-wireguard-on-openwrt)

2. [Networking](https://github.com/mikeroyal/WireGuard-Guide#networking)

3. [Docker](https://github.com/mikeroyal/WireGuard-Guide#docker)

4. [Kubernetes](https://github.com/mikeroyal/WireGuard-Guide#kubernetes)

5. [Ansible](https://github.com/mikeroyal/WireGuard-Guide#ansible)

6. [Microsoft Azure](https://github.com/mikeroyal/WireGuard-Guide#microsoft-azure)

7. [Amazon Web Services (AWS)](https://github.com/mikeroyal/WireGuard-Guide#amazon-web-services-aws)

8. [Google Cloud](https://github.com/mikeroyal/WireGuard-Guide#google-cloud-platform-gcp)


# Getting Started with WireGuard
[Back to the Top](#table-of-contents)

[WireGuard®](https://www.wireguard.com/) is a straight-forward, fast and modern VPN that utilizes state-of-the-art cryptography. It aims to be faster, simpler, leaner, and more useful than IPsec while avoiding the massive headache. WireGuard is designed as a general-purpose VPN for running on embedded interfaces and super computers alike, fit for many circumstances. Initially released for the Linux kernel, it is now cross-platform (Windows, macOS, BSD, iOS, Android) and widely deployable. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190848622-d1c8b109-f08c-4a89-b43d-816c510e4f2e.png">
  <br />
</p>

### Tutorials
[Back to the Top](#table-of-contents)

 * [Quick Start | WireGuard](https://www.wireguard.com/quickstart/)

 * [Virtual Private Networks — WireGuard | pfSense Documentation](https://docs.netgate.com/pfsense/en/latest/vpn/wireguard/index.html)
 
 * [How To Set Up WireGuard | DigitalOcean](https://www.digitalocean.com/community/tutorial_collections/how-to-set-up-wireguard)
 
 * [Linode Guides & Tutorials](https://www.linode.com/docs/guides/)
  
 * [Linode Beginner's Guide](https://www.linode.com/docs/guides/linode-beginners-guide/)
 
 * [Access a Pi-hole or Raspberry Pi from anywhere | Tailscale](https://tailscale.com/kb/1114/pi-hole/)
  
 * [Tailscale on Kubernetes | Tailscale](https://tailscale.com/kb/1185/kubernetes/)
  
 * [Tailscale on Proxmox host | Tailscale](https://tailscale.com/kb/1133/proxmox/)
  
 * [Configuring Linux DNS | Tailscale](https://tailscale.com/kb/1188/linux-dns/)
 
 * [WireGuard Introduction - John Hanley](https://www.jhanley.com/wireguard-introduction/)
 
 * [WireGuard Setup on Azure](https://pinloon.gitbook.io/wiki/vpn/wireguard-setup-on-azure)
 
 * [Creating a VPN Gateway with a Unikernel running WireGuard](https://nanovms.com/dev/tutorials/running-nanos-wireguard-vpn-gateway)
 
 * [Directions for setting up a WireGuard bounce server](https://gitlab.com/ncmncm/wireguard-bounce-server)
 
 * [How to easily configure WireGuard](https://www.stavros.io/posts/how-to-configure-wireguard/)
 
 * [Getting Started with WireGuard](https://miguelmota.com/blog/getting-started-with-wireguard/)

 * [Building a simple VPN with WireGuard with a Raspberry Pi as Server](https://snikt.net/blog/2020/01/29/building-a-simple-vpn-with-wireguard-with-a-raspberry-pi-as-server/)

 * [WireGuard on Kubernetes with Adblocking](https://codingcoffee.dev/blog/wireguard_on_kubernetes_with_adblocking/)
 
 * [Tunnel WireGuard via WebSockets](https://kirill888.github.io/notes/wireguard-via-websocket/)
 
 * [WireGuard Endpoint Discovery and NAT Traversal using DNS-SD](https://www.jordanwhited.com/posts/wireguard-endpoint-discovery-nat-traversal/)
 
 ### Books
 
 [Back to the Top](#table-of-contents)

 * [Linux Security Fundamentals by David Clinton](https://www.google.com/books/edition/Linux_Security_Fundamentals/WPkCEAAAQBAJ?hl=en&gbpv=0)
 
 * [Practical Linux Forensics: A Guide for Digital Investigators by Bruce Nikkel](https://www.google.com/books/edition/Practical_Linux_Forensics/TxhDEAAAQBAJ?hl=en&gbpv=0)
 
 * [Computing in Communication Networks From Theory to Practice by Fabrizio Granelli, Frank H.P. Fitzek, Patrick Seeling](https://www.google.com/books/edition/Computing_in_Communication_Networks/oXLnDwAAQBAJ?hl=en&gbpv=0)
 
 * [Security and Privacy in Communication Networks by Kevin Butler, Kun Sun, Nitesh Saxena, Noseong Park, Sara Foresti](https://www.google.com/books/edition/Security_and_Privacy_in_Communication_Ne/RYkOEAAAQBAJ?hl=en&gbpv=0)
 
 * [Kubernetes Security and Observability by Brendan Creane, Amit Gupta](https://www.google.com/books/edition/Kubernetes_Security_and_Observability/pXZKEAAAQBAJ?hl=en&gbpv=0)
 
### Podcasts

[Back to the Top](#table-of-contents)

 * [Open Source Security Podcast](https://podcasts.apple.com/us/podcast/open-source-security-podcast/id1151833659)

 * [Self-Hosted](https://www.jupiterbroadcasting.com/show/self-hosted/)
 
 * [Linux Unplugged](https://www.jupiterbroadcasting.com/show/linux-unplugged/)

### WireGuard Tools

[Back to the Top](#table-of-contents)

[Wireguard Dashboard](https://github.com/donaldzou/wireguard-dashboard) is a simple and easy to use WireGuard dashboard written in Python and Flask.

[WireGuard-Manager](https://github.com/complexorganizations/wireguard-manager) is a tool that enables you to build your own VPN in under a minute.

[WireGuard installer](https://github.com/angristan/wireguard-install) is a WireGuard VPN installer for Linux servers.

[Network Manager Wireguard](https://github.com/max-moser/network-manager-wireguard) is a Network-Manager VPN Plugin for WireGuard.

[Wireguard Manager](https://github.com/complexorganizations/wireguard-manager) is a tool that enables you to build your own vpn under a minute.

[Tailscale](https://github.com/tailscale) is a WireGuard-based app that makes secure, private networks easy for teams of any scale. It works like an [overlay network](https://tailscale.com/blog/how-tailscale-works/) between the computers of your networks using all kinds of [NAT traversal sorcery](https://tailscale.com/blog/how-nat-traversal-works/).

[Headscale](https://github.com/juanfont/headscale) is an open source, self-hosted implementation of the Tailscale coordination server.

[BoringTun](https://github.com/cloudflare/boringtun) is an implementation of the WireGuard® protocol designed for portability and speed. It's successfully deployed on millions of [iOS](https://apps.apple.com/us/app/1-1-1-1-faster-internet/id1423538627) and [Android](https://play.google.com/store/apps/details?id=com.cloudflare.onedotonedotonedotone&hl=en_US) consumer devices as well as thousands of Cloudflare Linux servers.

[PiVPN](https://pivpn.io/) is the simplest VPN installer, designed for [Raspberry Pi](https://www.raspberrypi.com).

[WireGuardStatusbar](https://github.com/aequitas/macos-menubar-wireguard) is a macOS menubar icon for WireGuard/wg-quick.

[Warp](https://blog.cloudflare.com/1111-warp-better-vpn/) is a free WireGuard VPN from Cloudflare that's trying to fix mobile Internet performance and security.

[Firezone](https://firezone.dev/) is a self-hosted WireGuard®-based VPN server and Linux firewall.

[LuCI](https://github.com/openwrt/luci) is an OpenWrt Configuration Interface.

[Dsnet](https://github.com/naggie/dsnet/) is a simple command to manage a centralised wireguard VPN. Similar to wg-quick but quicker with key generation + address allocation.

[WGctrl](https://github.com/WireGuard/wgctrl-go) is a package wgctrl enables control of WireGuard interfaces on multiple platforms.

[WGzero](https://github.com/finzzz/wgzero) is a zero overhead wireguard setup.

[WG make](https://github.com/tevino/wg-make) is a tool to help set up WireGuard based networks. Currently, it generates configurations for peers according to a single configuration file.

[Guard](https://github.com/stellarproject/guard) is a gRPC server for managing wireguard tunnels.

[Onetun](https://github.com/aramperes/onetun) is a user-space WireGuard port-forwarder -- access ports running on peers in your WireGuard network from any device; without having to install WireGuard locally or without root access (no iptables configs).

[Wireproxy](https://github.com/octeep/wireproxy) is a userspace WireGuard client that connects to a WireGuard peer, and exposes a SOCKS5 proxy. (Use cases: Setting up WG as a VPN requires special privilege. It tells the kernel to create a special network interface to handle WG connection.

[Mistborn](https://gitlab.com/cyber5k/mistborn) is a secure platform for easily standing up and managing your own cloud services: including firewall, ad-blocking, and multi-factor WireGuard VPN access.

[Mistborn CLI](https://gitlab.com/cyber5k/mistborn-cli) is a Command-line interface for [Mistborn](https://gitlab.com/cyber5k/mistborn).

[Wiretrustee](https://wiretrustee.com/) is a WireGuard®-based mesh network that connects your devices into a single private network.

[Wiresteward](https://github.com/utilitywarehouse/wiresteward) is a WireGuard peer manager with OAuth2 authentication.

[Innernet](https://github.com/tonarino/innernet) is a private network system that uses WireGuard under the hood.

[Autowire](https://github.com/elghazal-a/autowire) is a tool that automatically configure Wireguard interfaces in distributed system. It supports Consul as backend.

[Cloudblock](https://github.com/chadgeary/cloudblock) is a tool that deploys WireGuard VPN, Pi-Hole DNS Ad-blocking, and DNS over HTTPS in a cloud provider or locally using Terraform and Ansible.

[WireGuard Cloud Gateway](https://galaxy.ansible.com/consensus/wireguard_cloud_gateway) is an Ansible role for setting up Wireguard as a gateway VPN server for cloud networks.

[Ansible-role Wireguard](https://github.com/githubixx/ansible-role-wireguard) is an ansible role for installing WireGuard VPN. Supports Ubuntu, Debian, Archlinx, Fedora and CentOS.

[Terraform AWS Wireguard](https://github.com/jmhale/terraform-aws-wireguard) is a Terraform module to deploy WireGuard on AWS.

[Algo VPN](https://github.com/trailofbits/algo) is a set of Ansible scripts that simplify the setup of a personal WireGuard and IPsec VPN. It uses the most secure defaults available and works with common cloud providers.

[Pro Custodibus](https://www.procustodibus.com/features/) is a tool for managing WireGuard with a variety of business VPN (Virtual Private Network) use cases, such as site-to-site connectivity, secure remote access from anywhere, secure access to the cloud (Amazon Web Services, Google Cloud Platform, Microsoft Azure, etc), and more.

[Drago](https://seashell.github.io/drago) is a flexible configuration manager for WireGuard designed to make it simple to configure secure network overlays spanning heterogeneous nodes distributed across different clouds and physical locations. Drago is in active development, and we welcome contributions from the open-source community.

[Netmaker](https://github.com/gravitl/netmaker) is a VPN platform that automates WireGuard from homelab to enterprise. The key distinctions in their solutions are: fast because it can use kernel WireGuard (instead of userspace WireGuard, which is slower), tailored towards the Cloud and Kubernetes, and fully self-hostable.

[Kilo](https://github.com/squat/kilo) is a multi-cloud network overlay built on WireGuard and designed for Kubernetes. Kilo connects nodes in a cluster by providing an encrypted layer 3 network that can span across data centers and public clouds. The Pod network created by Kilo is always fully connected, even when the nodes are in different networks or behind NAT. By allowing pools of nodes in different locations to communicate securely, Kilo enables the operation of multi-cloud clusters. Kilo's design allows clients to VPN to a cluster in order to securely access services running on the cluster.

[Subspace](https://github.com/subspacecloud/subspace) is a simple WireGuard VPN server GUI.

[WG UI](https://github.com/EmbarkStudios/wg-ui) is a basic, self-contained management service for WireGuard with a self-serve web UI.

[WireHole](https://github.com/IAmStoxe/wirehole) is a combination of WireGuard, PiHole, and Unbound in a docker-compose project with the intent of enabling users to quickly and easily create and deploy a personally managed full or split-tunnel WireGuard VPN with ad blocking capabilities (via Pihole), and DNS caching with additional privacy options (via Unbound).

[Wireguard Config Generator](https://www.wireguardconfig.com/) is a tool that assist's with creating config files for a WireGuard 'road-warrior' setup whereby you have a server and a bunch of clients.

[Gluetun](https://github.com/qdm12/gluetun) is a lightwieght VPN client in a thin Docker container for multiple VPN providers, written in Go, and uses OpenVPN or Wireguard, DNS over TLS, with a few proxy servers built-in.

[Ethr](https://github.com/microsoft/ethr) is a cross platform network performance measurement tool written in golang. The goal of this project is to provide a native tool for comprehensive network performance measurements of bandwidth, connections/s, packets/s, latency, loss & jitter, across multiple protocols such as TCP, UDP, HTTP, HTTPS, and across multiple platforms such as Windows, Linux and other Unix systems.

### Setting up WireGuard with PiVPN

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190881122-3accce96-dbc1-46ba-9e67-bff78f160475.png">
  <br />
</p>

**Installing PiVPN:**

```sudo apt install curl -y```

```curl -L https://install.pivpn.io | bash```

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880700-48034b3b-c3d2-459e-b52b-ed5d699fe31a.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880702-9da353e8-2a25-4b9c-bb48-4d28af696e1e.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880703-5d71fb3c-1ad9-4511-bb21-da60da25c9d7.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880704-2042e18b-bc60-4b53-8251-2e3628b3083e.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880705-8270b271-2cf4-49b7-b133-a04509167425.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880706-401973df-8d3d-4c18-bd79-49948b8d1ee2.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880708-9c8aedf5-81bd-4f93-bf87-d5c713194b13.png">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880709-28f88ff7-38bf-4ebe-916c-8228c13050ea.png">
  <br />
</p>


### Setting up WireGuard on Unraid

[Back to the Top](#table-of-contents)

 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190881124-635b4c29-41c6-423d-bff9-07e811a5f319.png">
  <br />
</p>

 Select Apps, then search for WireGuard and install **Wireguard-Easy**.
 
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880956-9ad5d1e6-5905-46ec-9d94-6f1c0a42a997.jpg">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880957-d20e3fa1-b219-407a-b80b-b84cc59bb2a0.png">
  <br />
  VPN manager
</p>

 Almost all of the settings can stay as default, however, there are a few that we will modify.

   * Set the WG_HOST variable to be the IP address of your Unraid server.
   * If you’d like to modify the WireGuard port (51820), you can do that here.
   * Change the default Web GUI password. 
    
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880958-e5c2c3f8-fd85-47c5-beb4-cc06d19899b4.png">
  <br />
</p>

    
### Setting up WireGuard on pfSense
  
  [Back to the Top](#table-of-contents)
  
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190881128-e03216b9-ecc6-4c12-a41e-0de7d1b51579.png">
  <br />
</p>
   
   When looking at how to set up WireGuard on pfSense, the first thing that we need to do is install the package. Follow the instructions below to install the WireGuard package on pfSense.
   
<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880975-b103fead-2596-4819-bb82-18414baa4fb4.jpg">
  <br />
</p>


* Open the Package Manager and search for WireGuard, then Install the latest version of the package.

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880976-1c7d0b18-8e50-4072-8f32-a6991b7d3923.jpg">
  <br />
</p>

* After the package has installed, select VPN then WireGuard and under the Tunnels section, select Add Tunnel. 

* In the Tunnel Configuration, set the Description as WireGuard, the Listen Port as 51820, then Generate private and public keys.

* Copy the Public Key. We will need this for our client configuration.

* Create the tunnel, then select Settings, and ensure that Enable WireGuard is selected. Then Save and Apply. 

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880978-70ccc9f1-f5be-479a-9f95-234a4f90ee87.jpg">
  <br />
</p>

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190880979-6a1db7b4-bace-47ea-8ba5-43b375a821ba.jpg">
  <br />
</p>

### Setting up WireGuard on OpenWRT

[Back to the Top](#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190891717-a0972531-ec9d-4b7d-8543-2a68fb1792d2.png">
  <br />
</p>

**Quick Links:**

 * [WireGuard route all traffic through wireguard tunnel](https://openwrt.org/docs/guide-user/services/vpn/wireguard/all-traffic-through-wireguard)
 * [Automated WireGuard Server and Multi-client](https://openwrt.org/docs/guide-user/services/vpn/wireguard/automated)
 * [WireGuard basics](https://openwrt.org/docs/guide-user/services/vpn/wireguard/basics)
 * [WireGuard client](https://openwrt.org/docs/guide-user/services/vpn/wireguard/client)
 * [WireGuard extras](https://openwrt.org/docs/guide-user/services/vpn/wireguard/extras)
 * [WireGuard performance](https://openwrt.org/docs/guide-user/services/vpn/wireguard/performance)
 * [WireGuard Road-Warrior Configuration](https://openwrt.org/docs/guide-user/services/vpn/wireguard/road-warrior)
 * [WireGuard](https://openwrt.org/docs/guide-user/services/vpn/wireguard/start)
 * [WireGuard server](https://openwrt.org/docs/guide-user/services/vpn/wireguard/server)
 * [WireGuard peers](https://openwrt.org/docs/guide-user/services/vpn/wireguard/serverclient)
 * [Automated WireGuard site-to-site VPN configuration](https://openwrt.org/docs/guide-user/services/vpn/wireguard/site-to-site)
 

In your router’s webUI, navigate to System - Software, click Update lists:

In the Filter field, type WireGuard, locate and install the **wireguard, wireguard-tools, kmod-wireguard, and luci-app-wireguard packages.** **Note: The wireguard package is included in version 22.02.**

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190891718-b56b1152-2236-4d2c-bfbd-0f9f8f064e01.jpeg">
  <br />
</p>

**Generate WireGuard keypair**

 SSH into your router as ‘root’ ([OpenWrt Wiki](https://openwrt.org/docs/guide-quick-start/sshadministration)):

   ```ssh root@192.168.1.1```

 Generate WireGuard keys:

  ```wg genkey | tee privatekey | wg pubkey > publickey```
     
  ```chmod 600 privatekey```

  Note your Private & Public keys, you will need them later:

  ```cat privatekey```
    
  ``` cat publickey```

**Creating an Interface**

 Navigate to Network - Interface,

 Click the Add new interface... button and enter the following configuration:
   * Name - give it any name
   * Protocol - WireGuard VPN

 Create interface

 In the General Settings tab:
   * Bring up on boot - Checked
   * Private Key - copy and paste the generated previously Private key
   * IP Address - enter the WireGuard IP Address obtained in the Client Area ending with /32, e.g. 172.27.124.169/32
        
        
**Add a Firewall zone**

 Navigate to Network - Firewall

 Click the Add button and enter the following configuration:
   * Name - Give it any name
   *  Input - Reject
   *  Output - Accept
   *  Forward - Reject
   *  Masquerading - Checked
   *  MSS clamping - Checked
   *  Covered networks - select the previously created VPN tunnel interface
   *  Allow forward to destination zones - Unspecified
   *  Allow forward from source zones - lan
      
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190891722-8e64c915-9fbf-48e2-ae4d-73a1bd4c9489.jpeg">
  <br />
</p>
       
**DNS**

 Navigate to Network - Interfaces

 Click on the Edit button next to the WAN interface

  In the Advanced Settings tab, uncheck the Use DNS servers advertised by peer and specify one of the following DNS servers in the Use custom DNS servers field:
  
  * 172.16.0.1 = regular DNS with no blocking
  * 10.0.254.2 = standard AntiTracker to block advertising and malware domains
  * 10.0.254.3 = Hardcore Mode AntiTracker to also block Google and Facebook domains
      
 <p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/190891723-43aa1b88-ab91-4f87-935b-03f052add368.jpeg">
  <br />
</p> 

Click the Save button.

**Last Steps**

  * A device reboot is not required, though it may be useful to confirm that everything behaves as expected.
  * Run a leak test at [https://www.dnsleaktest.com](https://www.dnsleaktest.com/) via one of the internal network clients attached to your OpenWRT router.

# Networking
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/82833053-d1687b80-9e71-11ea-8c6d-074100f2f54b.png">
  <br />
</p>

## Networking Tools & Concepts

[Qt Network Authorization](https://doc.qt.io/qt-6/qtnetworkauth-index.html) is a tool that provides a set of APIs that enable Qt applications to obtain limited access to online accounts and HTTP services without exposing users' passwords.

[cURL](https://curl.se/) is a computer software project providing a library and command-line tool for transferring data using various network protocols(HTTP, HTTPS, FTP, FTPS, SCP, SFTP, TFTP, DICT, TELNET, LDAP LDAPS, MQTT, POP3, POP3S, RTMP, RTMPS, RTSP, SCP, SFTP, SMB, SMBS, SMTP or SMTPS). cURL is also used in cars, television sets, routers, printers, audio equipment, mobile phones, tablets, settop boxes, media players and is the Internet transfer engine for thousands of software applications in over ten billion installations.

[cURL Fuzzer](https://github.com/curl/curl-fuzzer) is a quality assurance testing for the curl project.

[DoH](https://github.com/curl/doh) is a stand-alone application for DoH (DNS-over-HTTPS) name resolves and lookups.

[Authelia](https://www.authelia.com/) is an open-source highly-available authentication server providing single sign-on capability and two-factor authentication to applications running behind [NGINX](https://nginx.org/en/).

[nginx(engine x)](https://nginx.org/en/) is an HTTP and reverse proxy server, a mail proxy server, and a generic TCP/UDP proxy server, originally written by Igor Sysoev.

[Proxmox Virtual Environment(VE)](https://www.proxmox.com/en/) is a complete open-source platform for enterprise virtualization. It inlcudes a built-in web interface that you can easily manage VMs and containers, software-defined storage and networking, high-availability clustering, and multiple out-of-the-box tools on a single solution.

[Wireshark](https://www.wireshark.org/) is a very popular network protocol analyzer that is commonly used for network troubleshooting, analysis, and communications protocol development. Learn more about the other useful [Wireshark Tools](https://wiki.wireshark.org/Tools) available.

[HTTPie](https://github.com/httpie/httpie) is a command-line HTTP client. Its goal is to make CLI interaction with web services as human-friendly as possible. HTTPie is designed for testing, debugging, and generally interacting with APIs & HTTP servers.

[HTTPStat](https://github.com/reorx/httpstat) is a tool that visualizes curl statistics in a simple layout.

[Wuzz](https://github.com/asciimoo/wuzz) is an interactive cli tool for HTTP inspection. It can be used to inspect/modify requests copied from the browser's network inspector with the "copy as cURL" feature.

[Websocat](https://github.com/vi/websocat) is a ommand-line client for WebSockets, like netcat (or curl) for ws:// with advanced socat-like functions.

   - Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.

   - Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.

Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

   - Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.

A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

   - LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.

   - WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

   - Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers.

Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

   - Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.

   - Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.

   - NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.

   - VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.

## Network Layers

While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.

As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.

One method of talking about the different layers of network communication is the OSI model. OSI stands for [Open Systems Interconnect](https://en.wikipedia.org/wiki/OSI_model).This model defines seven separate layers. The layers in this model are:

   - Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.

   - Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.

   - Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.

   - Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

   - Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.

   - Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.

   - Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).

The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

   - Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user.
The communication takes place between peers network.

   - Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.

   - Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.

   - Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.

### Interfaces
**Interfaces** are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Network Protocols

Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

**Media Access Control(MAC)** is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

**The IP protocol** is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

**ICMP: internet control message protocol** is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

**TCP: Transmission control protocol** is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

**UDP: User datagram protocol** is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

**HTTP: Hypertext transfer protocol** is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

**FTP: File transfer protocol** is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

**DNS: Domain name system** is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

**SSH: Secure shell** is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

[REST(REpresentational State Transfer)](https://www.codecademy.com/articles/what-is-rest) is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

# Docker
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521410-2e32c900-954e-11eb-8311-065fa0099546.png">
  <br />
</p>


<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113521413-2ffc8c80-954e-11eb-9d19-b9c996bc524b.png">
  <br />
</p>

**Container Architecture. Source: [Containerd.io](https://containerd.io)**

## Docker Learning Resources

[Docker Training Program](https://www.docker.com/dockercon/training)

[Docker Certified Associate (DCA) certification](https://training.mirantis.com/dca-certification-exam/)

[Docker Documentation | Docker Documentation](https://docs.docker.com/)

[The Docker Workshop](https://courses.packtpub.com/courses/docker)

[Docker Courses on Udemy](https://www.udemy.com/topic/docker/)

[Docker Courses on Coursera](https://www.coursera.org/courses?query=docker)

[Docker Courses on edX](https://www.edx.org/learn/docker)

[Docker Courses on Linkedin Learning](https://www.linkedin.com/learning/topics/docker)

## Docker Tools

[Docker](https://www.docker.com/) is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly working in collaboration with cloud, Linux, and Windows vendors, including Microsoft.

[Docker Enterprise](https://www.mirantis.com/software/docker/docker-enterprise/) is a subscription including software, supported and certified container platform for CentOS, Red Hat Enterprise Linux (RHEL), Ubuntu, SUSE Linux Enterprise Server (SLES), Oracle Linux, and Windows Server 2016, as well as for cloud providers AWS and Azure. In [November 2019 Docker's Enterprise Platform business was acquired by Mirantis](https://www.mirantis.com/company/press-center/company-news/mirantis-acquires-docker-enterprise/).

[Docker Desktop](https://www.docker.com/products/docker-desktop) is an application for MacOS and Windows machines for the building and sharing of containerized applications and microservices. Docker Desktop delivers the speed, choice and security you need for designing and delivering containerized applications on your desktop. Docker Desktop includes Docker App, developer tools, Kubernetes and version synchronization to production Docker Engines.

[Docker Hub](https://hub.docker.com/) is the world's largest library and community for container images Browse over 100,000 container images from software vendors, open-source projects, and the community.

[Docker Compose](https://docs.docker.com/compose/) is a tool that was developed to help define and share multi-container applications. With Docker Compose, you can create a YAML file to define the services and with a single command, can spin everything up or tear it all down.

[Docker Swarm](https://docs.docker.com/engine/swarm/) is a Docker-native clustering system swarm is a simple tool which controls a cluster of Docker hosts and exposes it as a single "virtual" host.

[Dockerfile](https://docs.docker.com/engine/reference/builder/) is a text document that contains all the commands a user could call on the command line to assemble an image. Using docker build users can create an automated build that executes several command-line instructions in succession.

[Docker Containers](https://www.docker.com/resources/what-container) is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another.

[Docker Engine](https://www.docker.com/products/container-runtime) is a container runtime that runs on various Linux (CentOS, Debian, Fedora, Oracle Linux, RHEL, SUSE, and Ubuntu) and Windows Server operating systems. Docker creates simple tooling and a universal packaging approach that bundles up all application dependencies inside a container which is then run on Docker Engine.

[Docker Images](https://docs.docker.com/engine/reference/commandline/images/) is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings. Images have intermediate layers that increase reusability, decrease disk usage, and speed up docker build by allowing each step to be cached. These intermediate layers are not shown by default. The SIZE is the cumulative space taken up by the image and all its parent images.

[Docker Network](https://docs.docker.com/engine/reference/commandline/network/) is a that displays detailed information on one or more networks.

[Docker Daemon](https://docs.docker.com/config/daemon/) is a service started by a system utility, not manually by a user. This makes it easier to automatically start Docker when the machine reboots. The command to start Docker depends on your operating system. Currently, it only runs on Linux because it depends on a number of Linux kernel features, but there are a few ways to run Docker on MacOS and Windows as well by configuring the operating system utilities.

[Docker Storage](https://docs.docker.com/storage/storagedriver/select-storage-driver/) is a driver controls how images and containers are stored and managed on your Docker host.

[Kitematic](https://kitematic.com/) is a simple application for managing Docker containers on Mac, Linux and Windows letting you control your app containers from a graphical user interface (GUI).

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.


# Kubernetes
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/95383873-a884d800-08a0-11eb-8eaf-57af5b119f56.png">
  <br />
</p>


## Kubernetes Learning Resources

[Kubernetes (K8s)](https://kubernetes.io/) is an open-source system for automating deployment, scaling, and management of containerized applications.

[Getting Kubernetes Certifications](https://training.linuxfoundation.org/certification/catalog/?_sft_technology=kubernetes)

[Getting started with Kubernetes on AWS](https://aws.amazon.com/kubernetes/)

[Kubernetes on Microsoft Azure](https://azure.microsoft.com/en-us/topic/what-is-kubernetes/)

[Intro to Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/kubernetes-dashboard)

[Azure Red Hat OpenShift ](https://azure.microsoft.com/en-us/services/openshift/)

[Getting started with Google Cloud](https://cloud.google.com/learn/what-is-kubernetes)

[Getting started with Kubernetes on Red Hat](https://www.redhat.com/en/topics/containers/what-is-kubernetes)

[Getting started with Kubernetes on IBM](https://www.ibm.com/cloud/learn/kubernetes)

[Red Hat OpenShift on IBM Cloud](https://www.ibm.com/cloud/openshift)

[Enable OpenShift Virtualization on Red Hat OpenShift](https://developers.redhat.com/blog/2020/08/28/enable-openshift-virtualization-on-red-hat-openshift/)

[YAML basics in Kubernetes](https://developer.ibm.com/technologies/containers/tutorials/yaml-basics-and-usage-in-kubernetes/)

[Elastic Cloud on Kubernetes](https://www.elastic.co/elastic-cloud-kubernetes)

[Docker and Kubernetes](https://www.docker.com/products/kubernetes)

[Running Apache Spark on Kubernetes](http://spark.apache.org/docs/latest/running-on-kubernetes.html)

[Kubernetes Across VMware vRealize Automation](https://blogs.vmware.com/management/2019/06/kubernetes-across-vmware-cloud-automation-services.html)

[VMware Tanzu Kubernetes Grid](https://tanzu.vmware.com/kubernetes-grid)

[All the Ways VMware Tanzu Works with AWS](https://tanzu.vmware.com/content/blog/all-the-ways-vmware-tanzutm-works-with-aws)

[VMware Tanzu Education](https://tanzu.vmware.com/education)

[Using Ansible in a Cloud-Native Kubernetes Environment](https://www.ansible.com/blog/how-useful-is-ansible-in-a-cloud-native-kubernetes-environment)

[Managing Kubernetes (K8s) objects with Ansible](https://docs.ansible.com/ansible/latest/collections/community/kubernetes/k8s_module.html)

[Setting up a Kubernetes cluster using Vagrant and Ansible](https://kubernetes.io/blog/2019/03/15/kubernetes-setup-using-ansible-and-vagrant/)

[Running MongoDB with Kubernetes](https://www.mongodb.com/kubernetes)

[Kubernetes Fluentd](https://docs.fluentd.org/v/0.12/articles/kubernetes-fluentd)

[Understanding the new GitLab Kubernetes Agent](https://about.gitlab.com/blog/2020/09/22/introducing-the-gitlab-kubernetes-agent/)

[Intro Local Process with Kubernetes for Visual Studio 2019](https://devblogs.microsoft.com/visualstudio/introducing-local-process-with-kubernetes-for-visual-studio%E2%80%AF2019/)

[Kubernetes Contributors](https://www.kubernetes.dev/)

[KubeAcademy from VMware](https://kube.academy/)

[Kubernetes Tutorials from Pulumi](https://www.pulumi.com/docs/tutorials/kubernetes/)

[Kubernetes Playground by Katacoda](https://www.katacoda.com/courses/kubernetes/playground)

[Scalable Microservices with Kubernetes course from Udacity ](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615)

## Kubernetes Tools, Frameworks, and Projects

[Open Container Initiative](https://opencontainers.org/about/overview/) is an open governance structure for the express purpose of creating open industry standards around container formats and runtimes.

[Buildah](https://buildah.io/) is a command line tool to build Open Container Initiative (OCI) images. It can be used with Docker, Podman, Kubernetes.

[Podman](https://podman.io/) is a daemonless, open source, Linux native tool designed to make it easy to find, run, build, share and deploy applications using Open Containers Initiative (OCI) Containers and Container Images. Podman provides a command line interface (CLI) familiar to anyone who has used the Docker Container Engine.

[Containerd](https://containerd.io) is a daemon that manages the complete container lifecycle of its host system, from image transfer and storage to container execution and supervision to low-level storage to network attachments and beyond. It is available for Linux and Windows.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for running containerized applications.

[Azure Kubernetes Service (AKS)](https://azure.microsoft.com/en-us/services/kubernetes-service/) is serverless Kubernetes, with a integrated continuous integration and continuous delivery (CI/CD) experience, and enterprise-grade security and governance. Unite your development and operations teams on a single platform to rapidly build, deliver, and scale applications with confidence.

[Amazon EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html) is a tool that runs Kubernetes control plane instances across multiple Availability Zones to ensure high availability.

[AWS Controllers for Kubernetes (ACK)](https://aws.amazon.com/blogs/containers/aws-controllers-for-kubernetes-ack/) is a new tool that lets you directly manage AWS services from Kubernetes. ACK makes it simple to build scalable and highly-available Kubernetes applications that utilize AWS services.

[Container Engine for Kubernetes (OKE)](https://www.oracle.com/cloud-native/container-engine-kubernetes/) is an Oracle-managed container orchestration service that can reduce the time and cost to build modern cloud native applications. Unlike most other vendors, Oracle Cloud Infrastructure provides Container Engine for Kubernetes as a free service that runs on higher-performance, lower-cost compute.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Red Hat Openshift](https://www.openshift.com/) is a fully managed Kubernetes platform that provides a foundation for on-premises, hybrid, and multicloud deployments.

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[Rook](https://rook.io/) is a tool that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal.

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances.

[Helm](https://helm.sh/) is a Kubernetes Package Manager tool that makes it easier to install and manage Kubernetes applications.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking.

[KubeFlow](https://www.kubeflow.org/) is a tool dedicated to making deployments of machine learning (ML) workflows on Kubernetes simple, portable and scalable.

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[MicroK8s](https://microk8s.io/) is a tool that delivers the full Kubernetes experience. In a Fully containerized deployment with compressed over-the-air updates for ultra-reliable operations. It is supported on Linux, Windows, and MacOS.

[Charmed Kubernetes](https://ubuntu.com/kubernetes/features) is a well integrated, turn-key, conformant Kubernetes platform, optimized for your multi-cloud environments developed by Canonical.

[Grafana Kubernetes App](https://grafana.com/grafana/plugins/grafana-kubernetes-app) is a toll that allows you to monitor your Kubernetes cluster's performance. It includes 4 dashboards, Cluster, Node, Pod/Container and Deployment. It allows for the automatic deployment of the required Prometheus exporters and a default scrape config to use with your in cluster Prometheus deployment.

[KubeEdge](https://kubeedge.io/en/) is an open source system for extending native containerized application orchestration capabilities to hosts at Edge.It is built upon kubernetes and provides fundamental infrastructure support for network, app. deployment and metadata synchronization between cloud and edge.

[Lens](https://k8slens.dev/)  is the most powerful IDE for people who need to deal with Kubernetes clusters on a daily basis. It has support for MacOS, Windows and Linux operating systems.

[Flux CD](https://fluxcd.io/) is a tool that automatically ensures that the state of your Kubernetes cluster matches the configuration you've supplied in Git. It uses an operator in the cluster to trigger deployments inside Kubernetes, which means that you don't need a separate continuous delivery tool.

[Platform9 Managed Kubernetes (PMK)](https://platform9.com/managed-kubernetes/) is a Kubernetes as a service that ensures fully automated Day-2 operations with 99.9% SLA on any environment, whether in data-centers, public clouds, or at the edge.

# Ansible
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113448802-62bd4e00-93b1-11eb-9114-419e758af23b.png">
  <br />
</p>

**[Mac Development Ansible Playbook by Jeff Geerling](https://github.com/geerlingguy/mac-dev-playbook)**

## Ansible Learning Resources

[Ansible](https://www.ansible.com/) is a simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. It uses a very simple language (YAML, in the form of Ansible Playbooks) that allows you to describe your automation jobs in a way that approaches plain English. Anisble works on Linux (Red Hat EnterPrise Linux(RHEL) and Ubuntu) and Microsoft Windows.

[Red Hat Training for Ansible](https://www.ansible.com/products/training-certification)

[Top Ansible Courses Online from Udemy](https://www.udemy.com/topic/ansible/)

[Introduction to Ansible: The Fundamentals on Coursera](https://www.coursera.org/projects/ansible-fundamentals)

[Learning Ansible Fundamentals on Pluralsight](https://www.pluralsight.com/courses/ansible-fundamentals)

[Introducing Red Hat Ansible Automation Platform 2.1](https://www.ansible.com/blog/introducing-red-hat-ansible-automation-platform-2.1)

[Ansible Documentation](https://docs.ansible.com/ansible/latest/index.html)

[Ansible Galaxy User Guide](https://docs.ansible.com/ansible/latest/galaxy/user_guide.html)

[Ansible Use Cases](https://www.ansible.com/use-cases?hsLang=en-us)

[Ansible Integrations](https://www.ansible.com/integrations?hsLang=en-us)

[Ansible Collections Overview](https://github.com/ansible-collections/overview/blob/main/README.rst)

[Working with playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html)

[Ansible for DevOps Examples by Jeff Geerling](https://github.com/geerlingguy/ansible-for-devops)

[Getting Started: Writing Your First Playbook - Ansible](https://www.ansible.com/blog/getting-started-writing-your-first-playbook)

[Working With Modules in Ansible](https://docs.ansible.com/ansible/latest/user_guide/modules.html)

[Ansible Best Practices: Roles & Modules](https://www.ansible.com/resources/webinars-training/ansible-best-practices-roles-modules)

[Working with command line tools for Ansible](https://docs.ansible.com/ansible/latest/user_guide/command_line_tools.html)

[Encrypting content with Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html)

[Using vault in playbooks with Ansible](https://docs.ansible.com/ansible/latest/user_guide/playbooks_vault.html)

[Using Ansible With Azure](https://docs.microsoft.com/en-us/azure/developer/ansible/overview)

[Configuring Ansible on an Azure VM](https://docs.microsoft.com/en-us/azure/developer/ansible/install-on-linux-vm)

[How to Use Ansible: An Ansible Cheat Sheet Guide from DigitalOcean](https://www.digitalocean.com/community/cheatsheets/how-to-use-ansible-cheat-sheet-guide)

[Intro to Ansible on Linode | Spatial Labs](https://spatial-labs.dev/posts/202101072328-intro-to-ansible-on-linode/)

## Ansible DevOps Tools Integration

[Ansible Automation Hub](https://www.ansible.com/products/automation-hub) is the official location to discover and download supported [collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections), included as part of an Ansible Automation Platform subscription. These content collections contain modules, plugins, roles, and playbooks in a downloadable package.

[Collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html#collections) are a distribution format for Ansible content that can include playbooks, roles, modules, and plugins. As modules move from the core Ansible repository into collections, the module documentation will move to the [collections pages](https://docs.ansible.com/ansible/latest/collections/index.html#list-of-collections).

[Ansible Lint](https://ansible-lint.readthedocs.io/en/latest/) is a command-line tool for linting playbooks, roles and collections aimed towards any Ansible users. Its main goal is to promote proven practices, patterns and behaviors while avoiding common pitfalls that can easily lead to bugs or make code harder to maintain.

[Ansible cmdb](https://github.com/fboender/ansible-cmdb) is a tool that takes the output of Ansible’s fact gathering and converts it into a static HTML overview page containing system configuration information.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) visually displays inventory inheritance hierarchies and at what level a variable is defined in inventory.

[Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) is a  command line tool to create a graph representing your Ansible playbook tasks and roles.

[Ansible Shell](https://github.com/dominis/ansible-shell) is an interactive shell for Ansible with built-in tab completion for all the modules.

[Ansible Silo](https://github.com/groupon/ansible-silo) is a self-contained Ansible environment by [Docker](https://www.docker.com/).

[Ansigenome](https://github.com/nickjj/ansigenome) is a command line tool designed to help you manage your Ansible roles.

[ARA](https://github.com/openstack/ara) is a records Ansible playbook runs and makes the recorded data available and intuitive for users and systems by integrating with Ansible as a callback plugin.

[Capistrano](https://capistranorb.com/documentation/overview/what-is-capistrano/) is a remote server automation tool. It supports the scripting and execution of arbitrary tasks, and includes a set of sane-default deployment workflows.

[Fabric](https://www.fabfile.org) is a high level Python (2.7, 3.4+) library designed to execute shell commands remotely over SSH, yielding useful Python objects in return. It builds on top of [Invoke](https://www.pyinvoke.org) (subprocess command execution and command-line features) and [Paramiko](https://paramiko.org/) (SSH protocol implementation), extending their APIs to complement one another and provide additional functionality.

[ansible-role-wireguard](https://galaxy.ansible.com/githubixx/ansible_role_wireguard) is an Ansible role for installing WireGuard VPN. Supports Ubuntu, Debian, Archlinx, Fedora and CentOS Stream.

[wireguard_cloud_gateway](https://galaxy.ansible.com/consensus/wireguard_cloud_gateway) is an Ansible role for setting up Wireguard as a gateway VPN server for cloud networks.

[Red Hat OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

# Microsoft Azure
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/143783606-58f4f708-dfe3-40f5-b9e3-c737479dc320.png">
  <br />
</p>

## Azure Learning Resources

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Get started with Azure](https://azure.microsoft.com/en-us/get-started/)

[Azure Demo and Q&A](https://azure.microsoft.com/en-us/get-started/webinar/)

[Microsoft Azure Training & Certification Courses](https://www.microsoft.com/en-us/learning/azure-training-certification.aspx)

[Azure on Microsoft Learn](https://docs.microsoft.com/en-us/learn/azure/)

[Microsoft Certified: Azure Fundamentals](https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/)

[Microsoft Certified: DevOps Engineer Expert Cert.](https://docs.microsoft.com/en-us/learn/certifications/devops-engineer)

[Introduction to Azure DevOps from A Cloud Guru](https://acloud.guru/learn/introduction-to-azure-devops)

[Microsoft Certified: Azure IoT Developer Specialty](https://docs.microsoft.com/en-us/learn/certifications/azure-iot-developer-specialty)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Microsoft Azure Certification Training Courses on Udemy](https://www.udemy.com/topic/microsoft-azure/)

[Free Microsoft Azure Courses & Tutorials on Udemy](https://www.udemy.com/topic/microsoft-azure/free/)

[Microsoft Azure Certification Training Courses on Coursera](https://www.coursera.org/learn/cloud-azure-intro)

[Microsoft Azure Certification Training Courses on edX](https://www.edx.org/learn/azure)

## Azure Tools

[Microsoft Azure Pricing Calculator](https://azure.microsoft.com/en-us/pricing/calculator/)

[Azure command-line interface (Azure CLI)](https://docs.microsoft.com/en-us/cli/azure/) is a command line that provides a set of commands used to create and manage Azure resources.

[Visual Studio Code](https://code.visualstudio.com/docs/azure/extensions) is a lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux. It comes with built-in support for JavaScript, TypeScript and Node.js and has a rich ecosystem of extensions for other languages (such as C++, C#, Java, Python, PHP, Go) and runtimes (such as .NET and Unity).

[Azure Functions](https://azure.microsoft.com/en-us/services/functions/) is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/what-is-azure-data-studio?view=sql-server-ver15) is a cross-platform database tool for data professionals using on-premises and cloud data platforms on Windows, macOS, and Linux. It offers a modern editor experience with IntelliSense, code snippets, source control integration, and an integrated terminal. It's engineered with the data platform user in mind, with built-in charting of query result sets and customizable dashboards.

[Azure Active Directory (Azure AD)](https://azure.microsoft.com/en-us/services/active-directory/) is Microsoft's cloud-based identity and access management service, which helps your employees sign in and access resources in: External resources, such as Microsoft 365, the Azure portal, and thousands of other SaaS applications.

[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) is a client tool that helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments.

[Azure Cognitive Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/) is a set of cloud-based services with REST APIs and client library SDKs available to help you build cognitive intelligence into your applications. You can add cognitive features to your applications without having artificial intelligence (AI) or data science skills. All it takes is an API call to embed the ability to see, hear, speak, search, understand, and accelerate decision-making into your apps.

[Azure Data Lake Storage](https://azure.microsoft.com/en-us/solutions/data-lake/) is a storage repository that holds a large amount of data in its native, raw format. Data lake stores are optimized for scaling to terabytes and petabytes of data. The data typically comes from multiple heterogeneous sources, and may be structured, semi-structured, or unstructured.

[Azure Service Fabric](https://azure.microsoft.com/en-us/services/service-fabric/) is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers. Service Fabric also addresses the significant challenges in developing and managing cloud native applications. It powers core Azure infrastructure as well as other Microsoft services such as Skype for Business, Intune, Azure Event Hubs, Azure Data Factory, Azure Cosmos DB, Azure SQL Database, Dynamics 365, and Cortana.

[Microsoft Azure Storage Emulator](https://docs.microsoft.com/en-us/azure/storage/common/storage-use-emulator) is a tool that emulates the Azure Blob, Queue, and Table services for local development purposes. You can test your application against the storage services locally without creating an Azure subscription or incurring any costs.

[Azure Cosmos DB Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator?tabs=cli,ssl-netstd21) is a tool that provides a local environment that emulates the Azure Cosmos DB service for development purposes. Using the Azure Cosmos DB Emulator, you can develop and test your application locally, without creating an Azure subscription or incurring any costs.

[Microsoft Azure Storage Explorer](https://www.storageexplorer.com/) is a standalone app that makes it easy to work with Azure Storage data on Windows, macOS, and Linux.

[Azure BatchExplorer](https://github.com/Azure/BatchExplorer#batchexplorer) is a  client tool to help create, debug and monitor Azure Batch Applications.

[Azure Key Vault Explorer](https://github.com/microsoft/AzureKeyVaultExplorer/blob/master/README.md)  is a  client tool to help be productive when working with secrets.

[Azurite](https://github.com/Azure/Azurite/blob/master/README.md) is an open source Azure Storage API compatible server (emulator). Based on Node.js, Azurite provides cross platform experiences for customers wanting to try Azure Storage easily in a local environment. Azurite simulates most of the commands supported by Azure Storage with minimal dependencies.

[Azure Cloud Shell](https://shell.azure.com/) is an interactive, authenticated, browser-accessible shell for managing Azure resources. It provides the flexibility of choosing the shell experience that best suits the way you work, either Bash or PowerShell.

[Azure Lab Services](https://azure.microsoft.com/en-us/services/lab-services/) is an easy to set up and provide on-demand access to preconfigured virtual machines (VMs) to support your scenarios. Teach a class, train professionals, run a hackathon or a hands-on lab, and more.

[Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines/) is a cloud-hosted pipelines for Linux, macOS, and Windows. Where you can build web, desktop and mobile applications. Deploy to any cloud or on‑premises.

[Azure Bots Service](https://azure.microsoft.com/en-us/services/bot-services/) is a service that develops intelligent, enterprise-grade bots that help you enrich the customer experience while maintaining control of your data. Build any type of bot—from a Q&A bot to your own branded virtual assistant—to quickly connect your users to the answers they need.

[Azure PlayFab](https://azure.microsoft.com/en-us/services/playfab/) is a service that enables developers to use the intelligent cloud to build and operate games, analyze gaming data and improve overall gaming experiences. Along with the Microsoft Game Stack that includes platforms, tools, and services like Visual Studio, DirectX, Havok, and Xbox.

[Azure Databricks](https://azure.microsoft.com/en-us/services/databricks/) is a tool that makes it fast, easy, and collaborative Apache Spark-based analytics platform. Azure Databricks, set up your Apache Spark™ environment in minutes, autoscale, and collaborate on shared projects in an interactive workspace. Azure Databricks supports Python, Scala, R, Java, and SQL, as well as data science frameworks and libraries including TensorFlow, PyTorch, and scikit-learn.

[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/) is an enterprise-grade machine learning service to build and deploy models faster. It empowers data scientists and developers with a wide range of productive experiences to build, train, and deploy machine learning models and foster team collaboration. Accelerate time to market with industry-leading MLOps—DevOps for machine learning. Innovate on a secure, trusted platform, designed for responsible machine learning.

[Azure Open Datasets](https://azure.microsoft.com/en-us/services/open-datasets/) is a tool that curates open data made easily accessible on Azure.

[Azure Percept](https://azure.microsoft.com/en-us/services/azure-percept/) is a comprehensive, easy-to-use platform with added security for creating edge AI solutions.

[Azure Data Share](https://azure.microsoft.com/en-us/services/data-share/) is a simple and safe service for sharing big data. It  provides full visibility into your data sharing relationships with a user-friendly interface. Share data in just a few clicks, or build your own application using the REST API.

[Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/) is a fully managed, serverless data integration solution for ingesting, preparing, and transforming all your data at scale.

[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/) is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. It gives you the freedom to query data on your terms, using either serverless or dedicated resources at scale.

[Azure HDInsight](https://azure.microsoft.com/en-us/services/hdinsight/) is an enterprise-ready, managed cluster service for open-source analytics.It let's you run popular open-source frameworks including Apache Hadoop, Spark, Hive, Kafka, and more.

[Azure Blockchain Service](https://azure.microsoft.com/en-us/services/blockchain-service/) is a service that simplifies the formation, management, and governance of consortium blockchain networks so you can focus on business logic and app development.

[Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/) is a leading integration platform as a service (iPaaS) enables key enterprise scenarios for developers. Built on a containerized runtime that increases scale and portability while automating business-critical workflows anywhere.

[Azure Quantum](https://azure.microsoft.com/en-us/services/quantum/) is an innovative quantum computing and optimization solutions converge in a single marketplace quantum service.

[Azure VMware Solution](https://azure.microsoft.com/en-us/services/azure-vmware/) is a service that seamlessly moves VMware-based workloads from your datacenter to Azure and integrate your VMware environment with Azure. Keep managing your existing environments with the same VMware tools you already know while you modernize your applications with Azure native services.

[Azure Spring Cloud](https://azure.microsoft.com/en-us/services/spring-cloud/) is a fully managed Spring Cloud service, jointly built and operated with VMware.

[Azure CycleCloud](https://azure.microsoft.com/en-us/features/azure-cyclecloud/) is a serviece that creates, manages, operates, and optimizes HPC and big compute clusters of any scale.

[Azure API Apps](https://azure.microsoft.com/en-us/services/app-service/api/) is a service that quickly builds and consumes APIs in the cloud using the language of your choice.

[Azure Web Apps](https://azure.microsoft.com/en-us/services/app-service/web/) is an easy way to create and deploy mission-critical web applications that scale with your business.

[Windows Virtual Desktop](https://azure.microsoft.com/en-us/services/virtual-desktop/) is a service that enables a secure, remote desktop experience from anywhere.

[VMware Horizon Cloud on Microsoft Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/vmware-horizon-cloud/) is a desktop virtualization service available in Azure Marketplace. Simplify your delivery of on-premises and cloud virtual desktops and applications by connecting your instance of Azure to VMware.

[Citrix Virtual Apps and Desktops for Azure](https://azure.microsoft.com/en-us/services/virtual-desktop/citrix-virtual-apps-desktops-for-azure/) is a desktop and app virtualization service available through Azure Marketplace or agreements with Citrix. Use familiar tools to manage on-premises Citrix deployments alongside Windows Virtual Desktop on Azure, supporting cloud modernization while maximizing your existing investment.

[Azure Container Registry](https://azure.microsoft.com/en-us/services/container-registry/) is a registry of Docker and Open Container Initiative (OCI) images, with support for all OCI artifacts.

[Azure Web App for Containers](https://azure.microsoft.com/en-us/services/app-service/containers/) is an easily deploy and run containerized applications on Windows and Linux.

[Azure SQL Edge](https://azure.microsoft.com/en-us/services/sql-edge/) is a service that makes a small-footprint, edge-optimized SQL database engine with built-in AI. This productivity tool for edge computing combines new capabilities such as data streaming and time series with in-database machine learning and graph features. Develop your application once and deploy anywhere across the edge, your datacenter, and Azure.

[Azure Arc](https://azure.microsoft.com/en-us/services/azure-arc/) is a service that offers simplified management, faster app development, and consistent Azure services. Standardize visibility, operations, and compliance across a wide range of resources and locations by extending the Azure control plane. Build cloud-native apps anywhere, at scale.

[Azure Artifacts](https://azure.microsoft.com/en-us/services/devops/artifacts/) is a services that provides fully integrated package management to your continuous integration/continuous delivery (CI/CD) pipelines with a single click. Create and share Maven, npm, NuGet, and Python package feeds from public and private sources with teams of any size.

[Azure Boards](https://azure.microsoft.com/en-us/services/devops/boards/) is a service that helps you plan, track, and discuss work across your teams. It let's you track work with Kanban boards, backlogs, team dashboards, and custom reporting.

[Azure ExpressRoute](https://azure.microsoft.com/en-us/services/expressroute/) is a tool that helps you experience a faster, private connection to Azure.

[Azure Sentinel](https://azure.microsoft.com/en-us/services/azure-sentinel/) is your birds-eye view across the enterprise. It uses the cloud and large-scale intelligence from decades of Microsoft security experience to work. Making your threat detection and response smarter and faster with artificial intelligence (AI).

[Azure Stack](https://azure.microsoft.com/en-us/overview/azure-stack/) is a service that builds and runs hybrid apps across datacenters, edge locations, remote offices, and the cloud.

[Azure Stack HCI](https://azure.microsoft.com/en-us/products/azure-stack/hci/) is a new hyperconverged infrastructure (HCI) operating system delivered as an Azure service that provides the latest security, performance, and feature updates. Deploy and run Windows and Linux virtual machines (VMs) in your datacenter or at the edge using your existing tools, processes, and skill sets.

[Azure Sphere](https://azure.microsoft.com/en-us/services/azure-sphere/) is a comprehensive IoT security solution including hardware (crossover microcontroller), OS, and cloud components for IoT device security to actively protect your devices, your business, and your customers.

[Azure IoT Hub](https://azure.microsoft.com/en-us/services/iot-hub/) is a service that provides a cloud-hosted solution back end to connect virtually any device. Extend your solution from the cloud to the edge with per-device authentication, built-in device management, and scaled provisioning.

[Azure IoT Edge](https://azure.microsoft.com/en-us/services/iot-edge/) is a fully managed service built on Azure IoT Hub. Deploy your cloud workloads—artificial intelligence, Azure and third-party services, or your own business logic to run on Internet of Things (IoT) edge devices via standard containers.

[Azure Lighthouse](https://azure.microsoft.com/en-us/services/azure-lighthouse/) is a secure managed services and access control for partners and customers.

[Azure Backup](https://azure.microsoft.com/en-us/services/backup/) is a cost-effective, secure, one-click backup solution that’s scalable based on your backup storage needs. The centralized management interface makes it easy to define backup policies and protect a wide range of enterprise workloads, including Azure Virtual Machines, SQL and SAP databases, and Azure file shares.

[Azure Resource Manager](https://azure.microsoft.com/en-us/features/resource-manager/) is a tool that enables you to repeatedly deploy your app and have confidence your resources are deployed in a consistent state. You define the infrastructure and dependencies for your app in a single declarative template. This template is flexible enough to use for all of your environments such as test, staging or production.

[Azure Automanage](https://azure.microsoft.com/en-us/services/azure-automanage/) is a tool that implifies IT management with optimized, automated operations across the entire lifecycle of dev/test and production virtual machines (VMs).

[Azure Network Watcher](https://azure.microsoft.com/en-us/services/network-watcher/) is a tool that monitors, diagnoses, and gains insights to your network performance and health.

[Azure Resource Mover](https://azure.microsoft.com/en-us/services/resource-mover/) is a that that Simplifies how you move multiple resources between Global Azure regions.

[Azure Bastion](https://azure.microsoft.com/en-us/services/azure-bastion/) is a fully managed PaaS service that provides secure and seamless RDP and SSH access to your virtual machines directly through the Azure Portal. Azure Bastion is provisioned directly in your Virtual Network (VNet) and supports all VMs in your Virtual Network (VNet) using SSL without any exposure through public IP addresses.

[Azure Load balancing](https://azure.microsoft.com/en-us/products/azure-load-balancing/) is a service that instantly scale your applications with Azure load balancing services for high availability and high performance. Get started with a quick needs assessment and load balancing recommendation—using the service selection tool.

[Azure Orbital](https://azure.microsoft.com/en-us/services/orbital/) is a Ground Station As-a-Service that provides communication and control of your satellite. Orbital enables easy and integrated data processing and scale for your operations directly from Azure. Leverage familiar Azure services to process and store your data at scale.

[Azure Route Server](https://azure.microsoft.com/en-us/services/route-server/) is a tool that enables network appliances to exchange route information with Azure virtual networks dynamically. Configure your network appliances and Azure ExpressRoute and VPN gateways to automatically take the latest route information from Azure Route Server instead of manually talking to each network.

[Azure VPN Gateway](https://azure.microsoft.com/en-us/services/vpn-gateway/) is a service that connects your on-premises networks to Azure through Site-to-Site VPNs in a similar way that you set up and connect to a remote branch office. The connectivity is secure and uses the industry-standard protocols Internet Protocol Security (IPsec) and Internet Key Exchange (IKE).

[Microsoft Azure Attestation](https://azure.microsoft.com/en-us/services/azure-attestation/) is a unified solution for remotely verifying the trustworthiness of a platform and integrity of the binaries running inside it. Azure Attestation receives evidence from the platform, validates it with security standards, evaluates it against configurable policies, and produces an attestation token for claims-based applications. The service supports attestation of trusted platform modules (TPMs) and trusted execution environments (TEEs) like Intel® Software Guard Extensions (SGX) and virtualization-based security (VBS) enclaves.

[Azure Data Box](https://azure.microsoft.com/en-us/services/databox/) is a device that easily moves data to Azure when busy networks aren’t an option. Move large amounts of data to Azure when you're limited by time, network availability, or costs, using common copy tools such as Robocopy. All data is AES-encrypted, and the devices are wiped clean after upload, in accordance with NIST Special Publication 800-88 revision 1 standards.

[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/) is a massively scalable and secure object storage for cloud-native workloads, archives, data lakes, high-performance computing, and machine learning.

[PowerShell/PowerShell Core](https://docs.microsoft.com/en-us/powershell/) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) creates virtual machines on Windows 10. Hyper-V can be enabled in many ways including using the Windows 10 control panel, PowerShell or using the Deployment Imaging Servicing and Management tool (DISM).

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.

[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.

# Amazon Web Services (AWS)
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114322508-7d8c7280-9ad5-11eb-807e-4dc63c9bc0e1.png">
  <br />
</p>


## AWS Learning Resources

[Amazon Web Services](https://aws.amazon.com/about-aws/) is a reliable, scalable, and inexpensive on-demand cloud computing platforms, services and APIs to individuals, companies, and governments, on a metered pay-as-you-go basis.

[AWS Training and Certification](https://aws.amazon.com/training/)

[Getting Started with Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/)

[Hands-On Tutorials for Amazon Web Services (AWS)](https://aws.amazon.com/getting-started/hands-on/

[Getting started with AWS IoT Core ](https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html)

[AWS Academy - Amazon Web Services (AWS)](https://aws.amazon.com/training/awsacademy/)

[AWS Educate](https://aws.amazon.com/education/awseducate/)

[Architecting on AWS Classroom Training](https://aws.amazon.com/training/classroom/architecting-on-aws/)

[DevOps Engineering on AWS from AWS Training](https://aws.amazon.com/training/course-descriptions/devops-engineering/)

[AWS Certified DevOps Engineer - Professional from A Cloud Guru](https://acloud.guru/learn/aws-certified-devops-engineer-professional)

[AWS Internet of Things Foundation Series Training](https://www.aws.training/Details/Curriculum?id=27289)

[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[AWS Certification Training Courses on Udemy](https://www.udemy.com/topic/aws-certification/)

[Amazon Web Services Courses on Coursera](https://www.coursera.org/aws)

[Amazon Web Services Courses on edX](https://www.edx.org/school/aws)

## AWS Tools

[AWS Pricing Calculator](https://calculator.aws/)

[AWS Marketplace](https://aws.amazon.com/) is a digital catalog with thousands of software listings from independent software vendors that make it easy to find, test, buy, and deploy software that runs on AWS.

[AWS Cloud9](https://aws.amazon.com/cloud9/) is a cloud-based integrated development environment (IDE) that lets you write, run, and debug your code with just a browser. It includes a code editor, debugger, and terminal. Cloud9 comes prepackaged with essential tools for popular programming languages, including JavaScript, Python, PHP, and more, so you don’t need to install files or configure your development machine to start new projects.

[AWS Command Line Interface (CLI)](https://aws.amazon.com/cli/) is a unified tool to manage your AWS services through the command line interface.

[AWS Amplify Command Line Interface (CLI)](https://docs.amplify.aws/cli) is a unified toolchain to create, integrate, and manage the AWS cloud services for your app.

[AWS Serverless Application Model (SAM) CLI](https://github.com/aws/aws-sam-cli) is a command line tool for an open-source framework for building serverless applications. It provides shorthand syntax to express functions, APIs, databases, and event source mappings. With just a few lines of configuration, you can define the application you want and model it.

[AWS Copilot command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/AWS_Copilot.html) is a command line tool that simplifies building, releasing, and operating production-ready containerized applications on Amazon ECS from a local development environment. The AWS Copilot CLI aligns with developer workflows that support modern application best practices: from using infrastructure as code to creating a CI/CD pipeline provisioned on behalf of a user.

[Amazon Elastic Container Service (Amazon ECS) command line interface (CLI)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ECS_CLI.html) is a command line tool that  provides high-level commands to simplify creating, updating, and monitoring clusters and tasks from a local development environment. The Amazon ECS CLI supports Docker Compose files, a popular open-source specification for defining and running multi-container applications.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Amazon Simple Storage Service (Amazon S3)](https://aws.amazon.com/s3/) is an object storage service that offers industry-leading scalability, data availability, security, and performance. This means customers of all sizes and industries can use it to store and protect any amount of data for a range of use cases, such as data lakes, websites, mobile applications, backup and restore, archive, enterprise applications, IoT devices, and big data analytics.

[AWS Cloud Development Kit (AWS CDK)](https://aws.amazon.com/cdk/) is an open-source software development framework to define cloud infrastructure in code and provision it through AWS CloudFormation. It offers a high-level object-oriented abstraction to define AWS resources imperatively using the power of modern programming languages.

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) is an easy-to-use service for deploying and scaling web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby, Go, and Docker on familiar servers such as Apache, Nginx, Passenger, and IIS.

[AWS IoT Greengrass](https://aws.amazon.com/greengrass/) is an Internet of Things (IoT) open source edge runtime and cloud service that helps you build, deploy, and manage device software. It is used for IoT applications on millions of devices in homes, factories, vehicles, and businesses.

[AWS CodeArtifact](https://aws.amazon.com/codeartifact/) is a fully managed artifact repository service that makes it easy for organizations of any size to securely store, publish, and share software packages used in their software development process. CodeArtifact can be configured to automatically fetch software packages and dependencies from public artifact repositories so developers have access to the latest versions.

[AWS CodeCommit](https://aws.amazon.com/codecommit/) is a fully-managed source control service that hosts secure Git-based repositories. It makes it easy for teams to collaborate on code in a secure and highly scalable ecosystem. CodeCommit eliminates the need to operate your own source control system or worry about scaling its infrastructure.

[AWS CodePipeline](https://aws.amazon.com/codepipeline/) is a fully managed [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin.

[AWS CodeStar](https://aws.amazon.com/codestar/) is a unified user interface, enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire [continuous delivery](https://aws.amazon.com/devops/continuous-delivery/) toolchain in minutes, allowing you to start releasing code faster.

[AWS X-Ray](https://aws.amazon.com/xray/) is a tool that traces user requests as they travel through your entire application. It aggregates the data generated by the individual services and resources that make up your application, providing you an end-to-end view of how your application is performing. It helps developers analyze and debug production, distributed applications, such as those built using a microservices architecture.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Red Hat OpenShift Service on AWS (ROSA)](https://www.openshift.com/products/amazon-openshift) is a fully-managed and jointly supported Red Hat OpenShift offering that combines the power of Red Hat OpenShift, the industry's most comprehensive enterprise Kubernetes platform, and the AWS public cloud.

[Amazon API Gateway](https://aws.amazon.com/api-gateway/) is a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.

[AWS Storage Gateway](https://aws.amazon.com/storagegateway/) is a hybrid cloud storage service that gives you on-premises access to virtually unlimited cloud storage.

[AWS Transit Gateway](https://aws.amazon.com/transit-gateway/) is a tool that connects VPCs and on-premises networks through a central hub. This simplifies your network and puts an end to complex peering relationships. It acts as a cloud router - each new connection is only made once.

[Gateway Load Balancer (GWLB)](https://aws.amazon.com/elasticloadbalancing/gateway-load-balancer/) is a tool that makes it easy to deploy, scale, and manage your third-party virtual appliances. It gives you one gateway for distributing traffic across multiple virtual appliances, while scaling them up, or down, based on demand.

[AWS Chalice](https://aws.amazon.com/blogs/developer/deploying-aws-chalice-application-using-aws-cloud-development-kit/) is a Python Serverless Microframework for AWS and allows you to quickly create and deploy applications that use Amazon API Gateway and AWS Lambda.

[AWS ParallelCluster](https://aws.amazon.com/hpc/parallelcluster/) is an AWS supported Open Source cluster management tool to deploy and manage HPC clusters in the AWS cloud.

[AWS Copilot CLI](https://aws.amazon.com/containers/copilot/) is a tool for developers to build, release and operate production ready containerized applications on Amazon ECS and AWS Fargate.

[AWS Fargate](https://aws.amazon.com/fargate/) is a serverless compute engine for containers that works with both Amazon Elastic Container Service (ECS) and Amazon Elastic Kubernetes Service (EKS).

[Amazon Chime](https://aws.amazon.com/chime/) is a communications service that lets you meet, chat, and place business calls inside and outside your organization, all using a single application.

[Amazon Virtual Private Cloud (Amazon VPC)](https://console.aws.amazon.com/vpc) is a service that lets you launch AWS resources in a logically isolated virtual network that you define. You have complete control over your virtual networking environment, including selection of your own IP address range, creation of subnets, and configuration of route tables and network gateways.

[AWS Lightsail](https://aws.amazon.com/lightsail/) is an easy-to-use virtual private server (VPS) that offers you everything needed to build an application or website, plus a cost-effective, monthly plan.

[Amazon Relational Database Service (Amazon RDS)](https://console.aws.amazon.com/rds/home) is a tool that makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks such as hardware provisioning, database setup, patching and backups.

[Amazon Aurora](https://console.aws.amazon.com/rds/home) is a MySQL and PostgreSQL-compatible relational database built for the cloud, that combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

[Amazon Athena](https://aws.amazon.com/athena/) is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. Athena is serverless, so there is no infrastructure to manage, and you pay only for the queries that you run.

[Amazon CloudSearch](https://aws.amazon.com/cloudsearch/) is a managed service in the AWS Cloud that makes it simple and cost-effective to set up, manage, and scale a search solution for your website or application.

[Amazon Kinesis](https://aws.amazon.com/kinesis/) is a tool that makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information. Amazon Kinesis offers key capabilities to cost-effectively process streaming data at any scale, along with the flexibility to choose the tools that best suit the requirements of your application. With Amazon Kinesis, you can ingest real-time data such as video, audio, application logs, website clickstreams, and IoT telemetry data for machine learning, analytics, and other applications.

Amazon EMR is the industry-leading cloud big data platform for processing vast amounts of data using open source tools such as [Apache Spark](https://aws.amazon.com/emr/features/spark/), [Apache Hive](https://aws.amazon.com/emr/features/hive/), [Apache HBase](https://aws.amazon.com/emr/features/hbase/), [Apache Flink](https://aws.amazon.com/blogs/big-data/use-apache-flink-on-amazon-emr/),[Apache Hudi](https://aws.amazon.com/emr/features/hudi/), and [Presto](https://aws.amazon.com/emr/features/presto/).

[AWS RedShift](https://aws.amazon.com/redshift/) is a data warehouse tool that makes it as easy to gain new insights from all your data. With Redshift, you can easily query and combine exabytes of structured and semi-structured data across your data warehouse, operational database, and data lake using standard SQL. It lets you easily save the results of your queries back to your S3 data lake using open formats, like Apache Parquet, so that you can do additional analytics from other analytics services like Amazon EMR, Amazon Athena, and Amazon SageMaker.

[AWS Data Pipeline](https://aws.amazon.com/datapipeline/) is a web service that helps you reliably process and move data between different AWS compute and storage services, as well as on-premises data sources, at specified intervals. AWS Data Pipeline, let's you regularly access your data where it’s stored, transform and process it at scale, and efficiently transfer the results to AWS services such as Amazon S3, Amazon RDS, Amazon DynamoDB, and Amazon EMR.

[AWS Glue](https://aws.amazon.com/glue/) is a serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.

[AWS Lake Formation](https://aws.amazon.com/lake-formation/) is a service that makes it easy to set up a secure data lake in days. A data lake is a centralized, curated, and secured repository that stores all your data, both in its original form and prepared for analysis.

[Amazon Managed Blockchain](https://aws.amazon.com/managed-blockchain/) is a fully managed service that makes it easy to join public networks or create and manage scalable private networks using the popular open-source frameworks [Hyperledger Fabric](https://aws.amazon.com/blockchain/what-is-hyperledger-fabric/) and Ethereum.

[AWS Wavelength](https://aws.amazon.com/wavelength/) is an AWS Infrastructure offering optimized for mobile edge computing applications. Wavelength Zones are AWS infrastructure deployments that embed AWS compute and storage services within communications service providers’ (CSP) datacenters at the edge of the 5G network, so application traffic from 5G devices can reach application servers running in Wavelength Zones without leaving the telecommunications network.

[AWS Outposts](https://aws.amazon.com/outposts/) is a fully managed service that offers the same AWS infrastructure, AWS services, APIs, and tools to virtually any datacenter, co-location space, or on-premises facility for a truly consistent hybrid experience. AWS Outposts is ideal for workloads that require low latency access to on-premises systems, local data processing, data residency, and migration of applications with local system interdependencies.

[AWS Batch](https://aws.amazon.com/batch/) is atool that enables developers, scientists, and engineers to easily and efficiently run hundreds of thousands of batch computing jobs on AWS. AWS Batch dynamically provisions the optimal quantity and type of compute resources (e.g., CPU or memory optimized instances) based on the volume and specific resource requirements of the batch jobs submitted. AWS Batch plans, schedules, and executes your batch computing workloads across the full range of AWS compute services and features, such as [AWS Fargate](https://aws.amazon.com/fargate/), [Amazon EC2](https://aws.amazon.com/ec2/) and [Spot Instances](https://aws.amazon.com/ec2/spot/).

[Amazon Forecast](https://aws.amazon.com/forecast/) is a fully managed service that uses machine learning to deliver highly accurate forecasts.

[AWS Snow Family](https://aws.amazon.com/snow/) is a highly-secure, portable devices to collect and process data at the edge, and migrate data into and out of AWS.

[Amazon Neptune](https://aws.amazon.com/neptune/) is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. The core of Amazon Neptune is a purpose-built, high-performance graph database engine optimized for storing billions of relationships and querying the graph with milliseconds latency.

[Amazon Timestream](https://aws.amazon.com/timestream/) is a fast, scalable, and serverless time series database service for IoT and operational applications that makes it easy to store and analyze trillions of events per day up to 1,000 times faster and at as little as 1/10th the cost of relational databases.

[AWS IoT](https://aws.amazon.com/iot/) is a service that is built on a secure and proven cloud infrastructure, and scales to billions of devices and trillions of messages. It easily integrates with other AWS services, so you can build complete solutions.

[AWS IoT Core](https://aws.amazon.com/iot-core/) lets you connect IoT devices to the AWS cloud without the need to provision or manage servers. AWS IoT Core can support billions of devices and trillions of messages, and can process and route those messages to AWS endpoints and to other devices reliably and securely.

#  Google Cloud Platform (GCP)
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

<p align="center">
 <img src="https://user-images.githubusercontent.com/45159366/114321928-639d6080-9ad2-11eb-8297-5e6c10c1c792.png">
  <br />
</p>

## Google Cloud Learning Resources

[Google Cloud Platform] is a public cloud platform that lets you build, deploy, and scale applications, websites, and services on the same infrastructure as Google.

[Google Cloud Courses and Training](https://cloud.google.com/training/)

[Architecting with Google Compute Engine](https://google.qwiklabs.com/courses/1421?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Get started with Cloud Storage on Web with Firebase](https://firebase.google.com/docs/storage/web/start)

[Getting started with BigQuery](https://cloud.google.com/bigquery/docs/quickstarts)

[Machine Learning Crash Course with Google Cloud](https://developers.google.com/machine-learning/crash-course/)

[Architecting with Google Kubernetes Engine in Google Cloud](https://google.qwiklabs.com/courses/1232?utm_source=gcp_training&utm_medium=website&utm_campaign=cgc)

[Google Cloud Internet of Things (IoT)](https://developers.google.com/iot/)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Google Cloud Courses on Coursera](https://www.coursera.org/googlecloud)

[Google Cloud Courses on Udemy](https://www.udemy.com/topic/google-cloud/)


## Google Cloud Tools

[Cloud SDK](https://cloud.google.com/sdk/) is a clietn tool used to to manage Google Cloud resources and applications with command-line tools and libraries. The Cloud SDK contains gcloud, gsutil, and bq command-line tools, which you can use to access [Compute Engine](https://cloud.google.com/compute), [Cloud Storage](https://cloud.google.com/storage), [BigQuery](https://cloud.google.com/bigquery), and more.

[Google Cloud Shell](https://cloud.google.com/shell/) is a free admin machine with browser-based command-line access for managing your infrastructure and applications on Google Cloud Platform.

[Cloud Code](https://cloud.google.com/code) is a client tool that writes, debugs, and run cloud-native applications, locally or in the cloud—quickly and easily. Extensions to IDEs such as Visual Studio Code and IntelliJ are provided to let you rapidly iterate, debug, and deploy code to Kubernetes.

[gcloud](https://cloud.google.com/sdk/gcloud/) is a CLI (command line interface) manages authentication, local configuration, developer workflow, interactions with Google Cloud APIs.

[gsutil](https://cloud.google.com/storage/docs/gsutil) is a Python application that lets you access Cloud Storage from the command line.

[Compute Engine](https://cloud.google.com/compute) is a secure and customizable compute service that lets you create and run virtual machines on Google’s infrastructure.

[App Engine](https://cloud.google.com/appengine/) is a client tool that lets you build and run applications on Google's infrastructure. It automatically scales to support sudden traffic spikes without provisioning, patching, or monitoring.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Cloud Storage](https://cloud.google.com/storage) is a Object storage for companies of all sizes. Where store any amount of data and retrieve it as often as you would like to.

[BigQuery](https://cloud.google.com/bigquery) is a serverless, highly scalable, and cost-effective multi-cloud data warehouse designed for business agility.

[Cloud Bigtable](https://cloud.google.com/bigtable/) is Google's fully managed NoSQL Big Data database service. It's the same database that powers many core Google services, including Search, Analytics, Maps, and Gmail.

[Cloud SQL](https://cloud.google.com/sql/) is a tool that makes it easy to set up, manage, and administer your Postgres databases on Google Cloud.

[Cloud Datastore](https://cloud.google.com/datastore/) is a schemaless database, which allows you to worry less about making changes to your underlying data structure as your application evolves.

[Cloud Pub/Sub](https://cloud.google.com/pubsub/) is a messaging middleware for traditional service integration or a simple communication medium for modern microservices.

[Cloud Dataflow](https://cloud.google.com/dataflow/) is a tool that brings streaming events to Google Cloud's AI Platform and TensorFlow Extended (TFX) to enable predictive analytics, fraud detection, real-time personalization, and other advanced analytics.

[Cloud Dataproc](https://cloud.google.com/dataproc/) is a fully managed and highly scalable service for running Apache Spark, Apache Flink, Presto, and 30+ open source tools and frameworks.

[Cloud Datalab](https://cloud.google.com/datalab/docs/) is a tool that provides a productive, interactive, and integrated tool to explore, visualize, analyze and transform data, bringing together the power of Python, SQL, JavaScript, and the Google Cloud Platform with services such as BigQuery and Storage.

[Cloud Vision API](https://cloud.google.com/vision/) is a library that offers powerful pre-trained machine learning models through REST and RPC APIs.

[Cloud Speech API](https://cloud.google.com/speech-to-text/) is a library that enables developers to convert audio to text by applying powerful neural network models. The API recognizes over 80 languages and variants, to support your global user base.

[Cloud Build](https://cloud.google.com/cloud-build) is a continuous build, test, and deploy software across all languages and in multiple environments—including VMs, serverless, Kubernetes, and Firebase.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[Jenkins on Google Cloud](https://cloud.google.com/jenkins) is a client tool that helps speed up, scale, and security from your Jenkins pipeline.

[Tekton on Google Cloud](https://cloud.google.com/tekton) is a client tool that standardizes CI/CD pipelines across languages, and tools on premises or in the cloud with a Kubernetes native open source framework.

[Artifact Registry](https://cloud.google.com/artifact-registry) is a client tool to manage container images and language packages such as Maven and npm all in one place, fully integrated with Google Cloud’s tooling and runtimes.

[Cloud Deployment Manager](https://cloud.google.com/deployment-manager) is a client that creates and manages cloud resources with simple templates. Specify all the resources needed for applications in a declarative format using yaml.

[Red Hat OpenShift on Google Cloud](https://cloud.google.com/solutions/partners/openshift-on-gcp) is a fully-managed and jointly supported Red Hat OpenShift offering that enables you to deploy stateful and stateless apps with nearly any language, framework, database, or service. It gives you a hosted environment entirely on Google Cloud. A hybrid environment where you maintain part of your workload on-premises or in a private hosting environment and migrate the rest to Google Cloud.

## Contribute

- [x] If would you like to contribute to this guide simply make a [Pull Request](https://github.com/mikeroyal/WireGuard-Guide/pulls).


## License
[Back to the Top](https://github.com/mikeroyal/WireGuard-Guide#table-of-contents)

Distributed under the [Creative Commons Attribution 4.0 International (CC BY 4.0) Public License](https://creativecommons.org/licenses/by/4.0/).

