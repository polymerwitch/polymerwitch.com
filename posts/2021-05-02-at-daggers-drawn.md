---
title: at-daggers-drawn
published_date: "2021-05-02 18:20:24 +0000"
layout: default.liquid
is_draft: false
---
# At Daggers Drawn With the VPN
## Its Defenders and Its False Critics

Much has been said about how great VPNs are for your privacy and security.
You need not look further than the paid promotion section of most Youtube videos.
Some have pushed against this and argued that you do not need a VPN at all.
I find that both of these arguments fail to speak of how a VPN can be extremely useful.
Of course, the title of this piece is a silly over exaggeration.
Not everyone needs a VPN, but many could benefit from one.
Lets explore the topic together and decide if our unique needs warrant a VPN.

## What is a VPN?

VPN stands for Virtual Private Network.
Lets break that down in reverse order:

### Network
A computer network is a group of connected computers.
Your home likely has a network where a number of computers, smart phones, and tablets all connect to a router (a special type of computer) and then use that to connect to the internet or even each other.
Your ISP has a network of many of those home networks.
The internet is just a network of all of those networks.

### Private
VPN technology uses encryption and security practices to keep your VPN network secure from the outside.
They are also meant to be used in a private way (for an individual or select group).

### Virtual
Unlike your home network that uses a combination of ethernet cables and radio waves (wifi) to connect to each other, VPNs connect computers together through software.

So, if we put this all together, a VPN is a software defined connection of computers that is meant for an individual or a select group.

VPNs can be configured in a nearly infinite number of ways. Do the computers in the VPN need to host web pages? Do they need to connect to the Internet? Do they need to connect to each other?

## What can a VPN do?

In a lot of schools and workplaces there are VPNs that allow people with credentials to connect to the institutions network from their home.
Now the computer is virtually part of the institutions network. This can give special access to private, intranet, web sites and services. It can also add the security of the institutions firewalls and other technologies to monitor for and prevent attackers.

Virtually being a part of a remote network can also allow your connection to the internet to come from that network.
This can be useful as other services and networks on the internet may filter based off what your origin network is.
It is also possible that your ISP uses network filters to prevent access to remote sites. A lot of networks value (or are forced by regulation to honor) neutrality in how they filter network traffic.
However, this isn't true of many mobile networks. This also doesn't account for legitimate reasons for filtering traffic.

Lets say you are on a school network and someone on the network is maliciously attacking the video site you are trying to watch.
In order to deal with the attack the video site temporarily filters out connections from your school. You may want a VPN to change you network so you can continue watching the video while your school deals with the attacker.

And speaking of malicious actors, if you are on the network at a hotel you could be vulnerable to people on the same network trying to attack your device on the low security hotel network. Having a VPN could allow you to move your public traffic to a more trusted network.

## Do I need a VPN?

It depends.

What use cases do you have? Are there services on another network that you need access to?
Do the security practices and filtering better meet your needs on another network?
What level of trust do you have with one network over another?

VPNs can give you access to private computer connections and the services they are running.
VPNs can create private networks to connect to other computers and allow you to connect to the internet through those computers.
VPNs can give you different network security which might be better or worse than what you already have.
VPNs can change the content you have access to if your local network or VPN network has differing filters.
VPNs can let your change your public IP address that the internet sees letting you bypass different websites filters (such as Netflix filtering content depending on what they think the country you are in is based off of your IP address).

VPNs don't always give you better privacy or security.
VPNs are not always trustworthy, but also are not always less trustworthy than your ISP.

So, if you have a specific need that a VPN can address, then it might be worth shopping around for a VPN that can meet that need.
For most use cases the service should not be more than a couple dollars a month.

## How do I trust a VPN has good security and privacy practices?

Do you know the people who run it? If it's ran by a friend or an organization you trust, then that could inform your decision.

You can also run your own VPN. The software is not hard to setup and is around the same price as most commercial VPNs.
Running your own VPN will allow you to build the security and privacy model you need.
It will also allow you to give private access to computers and services you have such as a personal home server running Nextcloud or Bitwarden.

However, it is important to note that even your own VPN will exist on someone else's larger network. If you setup your VPN on a cloud service, then that cloud service will need to be trusted.
If you run it from your house (for connecting to when out), then your ISP will need to be trusted. Still, you get to define the security practices on your VPN such that you understand exactly the limitations of privacy and security on it.

## What about Tor?

Tor, The Onion Router, also uses encryption and routes your traffic through a circuit of computers before reaching the internet.
This can make it extremely difficult for a third party to know where you are connecting to the internet from.
If you don't login to websites or transmit personally identifying information the chance of your connection being traced back to you is low.

This has limitations though. Some network traffic isn't well suited for the Tor network.
The various computers that make up your circuit to the internet usually have many connections, and your latency and speed will be limited to the slowest most latent connection in the circuit.
This also means that some protocols like bittorrent are not advised to use over the Tor network.
So, watching Netflix or playing a competitive game over Tor might not be a very pleasant experience for example.

Also, as the connection is shared, when your traffic exits the Tor network and goes back to the internet remote sites will think you are coming from that exit computer.
If others are being malicious on that exit computer (or even if the web sites just don't like Tor) they might filter out Tor traffic.

Finally, in places like the US we have some (not many) protections around the US government spying on us.
If you use Tor your traffic may exit to the internet in another country where the US government is free to collect this data.
In fact, official documents in the US have revealed that Tor data is especially monitored by the state.
So, you get anonymity in a highly surveilled network.

Tor is a useful tool if used correctly, but it is not the correct tool for all network security needs.

## Conclusion

I think VPNs are extremely useful. I also think how they are marketed is often misleading.
I hope you have enough information to consider if a VPN is something you want, and if so what type of VPN solution is right for you.
In a world with more and more computer devices that connect to networks having power over how and where they connect to each other and the world can be very powerful. VPNs are a great tool to help with this that are often misunderstood and misused.
