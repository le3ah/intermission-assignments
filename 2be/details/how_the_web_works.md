## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
  The browser and operating system will determine whether or not they know the IP address for that URL. It could be configured on the computer or could be in the memory cache.  If they don't know what the IP address is, the operating system is configured to ask the resolving name server.  The Resolving Name Server may or may not have this information; if it does not, then it will query the root name servers, as knowing where to find the root is the only thing Resolving name servers should know.  If the root name server does not have the appropriate information, the resolving name server will query the com name server, also known as the Top Level Domain (TLD) name server.  The resolving name server takes all of this information into its cache and will query the Authoritative Name Servers (ANS) with the help of the Domain's registrar.  The ANS will then be able to provide the resolving name server with a specific IP address for the website.  The resolving name server puts the IP address in cache and responds to the operating system with this information.
1.  What does HTTP stand for?
  Hypertext Transfer Protocol
1. 	What protocol does the World Wide Web use?
  The worldwide web hinges on three enabling protocols, the HyperText Markup Language (HTML) that specifies a simple markup language for describing hypertext pages, the HyperText Transfer Protocol (HTTP) which is used by web browsers to communicate with web clients, and Uniform Resource Locators (URLs) which are used to specify the links between documents.
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
  Internet Protocol
1. 	What does DNS stand for?
  * A. Domain Name System
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service
  **A**
1. 	How are text domain names matched to their respective numeric IP addresses.
  When a computer is connected to a network, it is automatically assigned an IP address.  In the same way that a phone number is split into an area code and an id code, an IP address is split into a Network Code and a Host ID.  Each IP address is directly addressable, so any router can direct your packet of information to any other part of the internet.  The text domain names are also unique identifiers mapped to the IP address.

1. 	What is the client?
  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * C. The software which requests information from a server (browser)
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to
    **C**
1. 	What does URL stand for?
  Uniform Resource Locator
1. 	What are protocols
 * A. The standardisation of IP addressess
 * B. The DNS standard method for data transfer
 * C.	The standardised network address system
 * D.	The standardised method for transferring data or documents over a network
 * E.	The standardised method for prioratising data or document storage over a network
 **D**
1. What does DNS stand for?
  Domain Name System
1. what is the `www` portion of a url?
  subdomain
1. What is The markup language used for all web documents?
  HTML (HyperText Markup Language)
1. What is the organization that monitors web technologies?
  World Wide Web Conrtium (W3C)
1. What is the Protocol for transferring web documents on the Internet?
  HTTP (HyperText Transfer Protocol)
1. What matches the domain names with numeric IP addresses?
  DNS (Domain Name System)
