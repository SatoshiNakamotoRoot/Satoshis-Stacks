# Blockstack

[![Slack](http://slack.blockstack.org/badge.svg)](http://slack.blockstack.org/)

## Table of Contents

- [Overview](#overview)
- [Code](#code)
- [Tutorials](#tutorials)
- [Papers](#papers)
- [Articles](#articles)
- [Community](#community)
- [Events](#events)
- [Requests for Comments](#requests-for-comments)
- [How to Help](#how-to-help)

### Overview

Blockstack is a movement to build the decentralized web - a movement of hackers, designers, and entrepreneurs from around the world deeply committed to the future of the Internet as a bastion of innovation, freedom, and economic inclusion. Blockstack is about pushing power to the edges with decentralized applications and allowing users to be in control of their data, identities and software.

Blockstack has protocols and software projects that when used together are a powerful way for developers to build decentralized, server-less applications, without having to rely on third parties. Blockstack Core provides decentralized naming, public key infrastructure, and storage. Blockstack Auth provides support for decentralized identity and authentication. Blockstack clients like the Blockstack CLI, Onename, and the Blockstack Browser provide complete packages that hook into Blockstack Core and Blockstack Auth.

<p>
    <a href="https://blockstack.org/docs">
        <img src="/images/documentation-site-2x.png" data-canonical-src="/images/documentation-site-2x.png" width="250" height="62" />
    </a>
</p>
<p>
    <img src="https://raw.githubusercontent.com/blockstack/blockstack/master/images/bsk-architecture-diagram3.png" data-canonical-src="https://raw.githubusercontent.com/blockstack/blockstack/master/images/bsk-architecture-diagram3.png" />
</p>

### Code

If you're just starting with Blockstack, here are the main repositories you should checkout: 

- [Blockstack Core](https://github.com/blockstack/blockstack-core) - the server that handles the core functionality of the decentralized domain name system and has an external storage system built-in for storing data records off-chain
- [Blockstack CLI](https://github.com/blockstack/blockstack-cli) - a CLI and client library that provides an interface for interacting with Blockstack servers and performing decentralized DNS operations
- [Blockstack Website](https://github.com/blockstack/blockstack-site) - the code for the official Blockstack website (found at blockstack.org)
- Blockstack Browser - the reference browser for browsing the Blockstack decentralized internet (coming soon)

After you've gotten familiar with the components above, you may want to take a deeper dive. Below you'll find some supporting libraries to dig into:

- [Virtualchain](https://github.com/blockstack/virtualchain) - a Python library for creating virtual blockchains on top of any underlying blockchain
- [Blockstack Auth JS](https://github.com/blockstack/blockstack-auth-js) - a JS library for generating and verifying auth requests and responses
- [Blockstack Bootstrap](https://github.com/blockstack/blockstack-bootstrap) - a fork of Bootstrap in the Blockstack

### Tutorials

- CLI (Command Line Interface)
  - [Installation](https://blockstack.org/tutorials/installation)
  - [Basic Usage](https://blockstack.org/tutorials/basic-usage)
  - [Extended Usage](https://blockstack.org/tutorials/extended-usage)
- Decentralized Apps
  - [Hello World](https://blockstack.org/tutorials/hello-world)

### Papers

- ["Blockstack: A Global Naming and Storage System Secured by Blockchains"](https://github.com/blockstack/blockstack/blob/master/papers/blockstack_usenix16.pdf), Proc. USENIX Annual Technical Conference (ATC ’16), June 2016
- ["Extending Existing Blockchains with Virtualchain"](https://github.com/blockstack/blockstack/blob/master/papers/virtualchain_dccl16.pdf), Proc. Workshop on Distributed Cryptocurrencies and Consensus Ledgers (DCCL '16), July 2016
- ["Bootstrapping Trust in Distributed Systems with Blockchains"](https://github.com/blockstack/blockstack/blob/master/papers/blockstack_login16.pdf), USENIX ;login: Magazine (pre-print)

### Articles

- [What is Blockstack Core?](https://blockstack.org/articles/blockstack-core)
- [How Blockstack Works](https://blockstack.org/articles/how-blockstack-works)

With the Blockstack software, a network of computers collectively maintain a global registry of names. When you run a Blockstack node, you join this network, which is more secure by design than traditional DNS and identity systems. This is because the system's registry and its records are secured by an underlying blockchain, which is extremely resilient against tampering and control.

In the registry that makes up Blockstack, each of the names has an owner, represented by a cryptographic keypair, and is associated with instructions for how DNS resolvers and other software should resolve the name.

Blockstack is already being used in production and currently [more than 60,000 names](https://resolver.onename.com/v2/namespaces) have been registered using it.

### Community

- [Slack Group](http://chat.blockstack.org) - Live chat with other Blockstackers
- [Meetup Groups](http://www.meetup.com/topics/blockstack/) - Join Meetup groups around the world
- [Subreddit](https://www.reddit.com/r/blockstack) - Share and discuss on the subreddit
- [Blog](https://blog.blockstack.org/) - Read posts by community members
- [YouTube](https://www.youtube.com/channel/UC3J2iHnyt2JtOvtGVf_jpHQ) - Watch videos on the YouTube channel
- [Twitter](https://twitter.com/blockstackorg) - Follow the tweets of the Blockstack community

### Events

- [Events](/events)
    - [Blockstack Meetups](/events/meetups.md)
    - [Non-Blockstack Events](/events/external-events.md)
    - [Past Events](/events/past-events.md)
    - [Past Meetups](/events/past-meetups.md)
    - [Event Checklist](/events/event-checklist.md)
    - [Swag](/events/swag.md)

### Requests for Comments

- [Blockstack RFCs](/blockstack-rfcs.md)

### How to Help

- **Contribute code** - all Blockstack software is free and open source, so send us pull requests if you have any suggestions for ways the software can be improved
- **Help with software testing** - we really appreciate and value our testers, and encourage people who want to support Blockstack to run the software and file issues in the appropriate repository for any bugs that are found
- **Improve the documentation** - we can never have enough documentation so if there's anything you'd like to clarify or add, just fork any of the Blockstack repos, start writing and expanding on the docs, and submit a pull request
- **Organize community events** - we welcome anyone interested in putting together anything as simple as a meetup at a local library or community center to discuss the latest Blockstack developments and applications with like-minded people from your area
- **Produce and share content** - if you have ideas or insights about Blockstack or decentralized applications in general, write a post and submit it to theBlockstack community blog or share it in the forum
