What information can I get from an IP address?
We've encountered a wide range of questions and assumptions about what information you can find regarding an IP address. We decided to go ahead and create a detailed guide on the IP address information overview.

https://ipinfo.io/ip-address-information

IP Address basics
At its core, an IP address is quite similar to a physical street address. It allows other devices to identify and connect to the device at the IP address. Perhaps without you realizing it, your web browser has connected to multiple IP addresses in order for you to read this post and you are using multiple IP addresses yourself.

Types of IP Addresses
IPv4 vs IPv6 Addresses
When most of us starting connecting to this amazing thing we call the Internet, we were all using IPv4 addresses. An IPv4 address looks something like 216.239.32.21 and there are 4,294,967,296 (2^32) addresses in total. When originally deployed in 1983, it was assumed that 4.2 billion IP addresses would be more than sufficient for us to use. Turn the clock to 2020 and we've exhausted all 4.2 billion IPv4 addresses.

Starting in the late 1990s, the Internet Engineering Task Force (IETF) began addressing the impending IPv4 address exhaustion and created IPv6. While your typical IPv4 address looks like 216.239.32.21, an IPv6 address looks like 2001:0db8:0000:0000:0000:ff00:0042:8329. The biggest and most important difference is that IPv6 allows us to go from 4.2 billion addresses to 340,300,...,000 (2^128) addresses. In case you were wondering, that's called 340 Undecillion.

While IPv6 should allow for every single internet-connected device its own IP address for the foreseeable future, IPv6 and IPv4 are not compatible so the adoption has been slower than IETF and others had hoped for. We could do an entire post on that alone.

Dynamic vs Static IP Addresses
Because the transition to IPv6 has been slow, most of us are using dynamic IP addresses. This means that your phone, router, etc may have its IP address changed periodically. When this happens you don't even notice. Unless you're hosting a server this doesn't impact you. If you stumbled upon this because you are hosting a server and your dynamic IP address makes it hard for people to connect to you, check out a Dynamic DNS service such as noip.com

Some people (and typically businesses) have what's called a static IP address. While a dynamic IP address may change, a static IP address does not. The pros and cons of a dynamic vs static IP address are another topic we could make an entire post on.

Public vs Private IP Addresses
While most IP addresses are public, meaning that people from all over the world can connect to it (just like you connected to a number of IP addresses to read this post), there are some ranges that have been set aside for private use. The best example is if you have a router you connect your phone or computer to. The private IP ranges for IPv4 are:

10.0.0.0 – 10.255.255.255

172.16.0.0 – 172.31.255.255

192.168.0.0 – 192.168.255.255

If you have a router, you can have 192.168.1.1 and I can have the same address.

Full IP address information
The reason that our amazing customers use IPinfo is because of the incredible information you can learn about a single IP address. Using our basic service, I looked up my IP address as I was writing this at Starbucks (Trenta water with either a Grande Americano or Grande Caramel Machiatto in case you're wondering) and this is what our services at IPinfo provided:

![alt text](image.png)


The Basics - Geolocation
Most of this information is straight forward, I want to make note that if you look up the latitude/longitude listed, you won't find a Starbucks on the map. Why is that? IP address geolocation is aimed at city or postal code level, not at the exact physical location.

ip: "47.37.71.230"
hostname: "47-37-71-230.dhcp.ftwo.tx.charter.com"
city: "Granbury"
region: "Texas"
country: "US"
loc: "32.4488,-97.7285"
postal: "76049"
timezone: "America/Chicago"
ASN API
With an ASN you can learn when it was allocated ownership of the IP, how many IPs they own, their main domain, business name, and what type of entity they are.

ip: "8.8.4.4"
asn: "AS15169"
name: "Google LLC"
domain: "google.com"
route: "47.37.64.0/18"
type: "business"
Hosting Data
More information about who is hosting/providing this IP address

ip: "108.8.4.4"
host: "mcicommunicationsservices"
id: "VIS-BLOCK"
name: "MCI Communications Services, Inc. d/b/a Verizon Business"
network: "108.0.0.0-108.57.255.255"
Company Data
Exactly what you think it is

name: "Charter Communications"
domain: "chartercom.com"
type: "isp"
Privacy API
This service allows you to learn whether or not the IP address in question is likely coming from a provider that is providing privacy services to the actual end user. IP address: 43.241.71.120

vpn: false
proxy: false
tor: false
relay: false
hosting: true
service: ""
Abuse Contact API
Is this API address engaging in some type of abuse, such as hacking, hosting copyrighted material, etc? You can quickly find out who to contact to report this behavior.

address: "US, CO, Greenwood Village, P.O. Box 4987, 80155"
country: "US"
email: "abuse@charter.net"
name: "Abuse"
network: "47.32.0.0-47.51.255.255"
phone: "+1-855-222-7342"
Common Questions on IP Information
The most common questions we see around learning about an IP address are:

Q: How do I look up information on a specific IP address? A: That's exactly what IPinfo is all about. Once you create an account, you can use our web-based tool in your account at https://ipinfo.io/account. Simply type in the IP address and we'll take care of the rest.

Q: How someone can use IP address information? What can someone do with your IP address? A: We have amazing customers doing some incredible things with this information, from providing geo-specific content to security research to learning more about their customers and habits based on location.

Q: Can I track the physical location of my phone or an individual person based on their IP address? A: In short, no, not really. You can get a general idea of where your phone is, but to track it down to the table it is sitting on is not really feasible. For those of you like myself who value privacy, this should come as a relief.

If you have more questions regarding IP address information, we'd love to hear there. We are constantly learning and developing incredible tools to help our customers makes the most of the Internet and the data out there. We'd love to see what ideas you have.