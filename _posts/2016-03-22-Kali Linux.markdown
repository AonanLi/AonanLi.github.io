---
title:  "Wireless Security Experiment Based on Kali Linux"
subtitle: "Kali Linux, Aircrack-ng, mitmproxy, sslstrip, arpspoof, nmap"
author: "Aonan Li"
avatar: "img/authors/aonan.png"
image: "img/20160322.jpg"
date:   2016-03-22 12:12:12
---

### Fulltext Paper
<a href="https://drive.google.com/file/d/0B1t9pF1wONA0d1ZMWnBNdk5Vczg/preview"><i class="fa fa-file-pdf-o fa-3x"></i></a>

### Introduction
In 1988, the IEEE organized a committee to develop the 802.11 standard. All the 802 standards deal with the data link layer and physical layer of the OSI reference model while Part 11 defines all the specifications for wireless networks. The initial 802.11 standard included one method of encryption, which was called "Wired Equivalence Privacy". Wired Equivalent Privacy (WEP) is a security algorithm used for protecting wireless networks from hackers who are going to get access free Internet access and retrieve confidential information. However, WEP is easy to be cracked as hacking methods develop, which results in a few fixes to the WEP protocol. Although WEP can always be supplemented with adding another layer of security above it such as IPsec or SSL, these fixes did not really address any of the fundamental flaws with WEP directly.

This situation led to two more protocols: Wi-Fi Protected Access (WPA) and WPA2, which were built from the ground up to replace WEP. These two approaches provided more secure mechanisms which required more complicated configurations to increase the security level. In order to simplify the configuration process, the Wi-Fi Protected Setup (WPS) was proposed which provided less configuration. However, WPS is vulnerable to brute force attacks, which can help hackers retrieve WPA/WPA2 login information and other credential information.

This paper provides a wireless security experiment based on Kali Linux, which is a Debian-based Linux distribution designed for penetration testing. It is preinstalled with over 300 penetration tools including Aircrack-ng, mitmproxy, sslstrip, and arpspoof, which are used in this experiment. The goal of this work is to summarize and discuss common methods of wireless attack by designing an experiment. This paper is organized as follow: Section II lists background information like a brief introduction to tools that are used, as well as a literature review of several related studies .Section III presents the contribution of this paper including detailed methodology, discussion and results. Section IV addresses the conclusion of this paper as well as future work.