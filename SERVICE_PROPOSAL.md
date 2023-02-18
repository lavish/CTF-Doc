Service Name
============

[comment]: # (The service name shouldn't be longer than 20 chars)

Authors:
* Name Surname, Author 1
* Name Surname, Author 2
* ...

Categories:
* Topic 1
* Topic 2
* ...

[comment]: # (Topics typically correspond to the vulnerabilities of each flag store, e.g., web, pwn, rev, crypto, etc. You are encouraged to implement different topics on each service, for instance by combining Web vulnerabilities with binary exploitation, or cryptography and reversing, and so on)


Overview
--------

[comment]: # (Include an exhaustive overview of the service and its intended functionalities. Explain in detail the technological stack that you plan to adopt, but do not introduce the vulnerabilities yet)

### Flag Store 1

[comment]: # (Detail how flags are stored and what do they represent. Explain if you plan to use flag IDs and how)

...

### Flag Store N

[comment]: # (Detail how flags are stored and what do they represent. Explain if you plan to use flag IDs and how)


Vulnerabilities
---------------

[comment]: # (Provide a high-level description of the vulnerabilities affecting each flag store. Include a proof-of-concept of the exploit, or - if this is not possible - a description of the attack flow. For each *vulnerability*, specify the intended difficulty level of the exploit, its *discoverability* by inspecting traffic dumps, etc., and *patchability*. Accepted values are *easy*, *medium*, *hard*. Vulnerabilities that are easy to exploit should be also easy to patch. On the other hand, it is fine to require more complex patches if the difficulty is also hard. It is also fine to keep the pathcability as easy if the discoverability is hard. Concerning discoverability, as a rule of thumb, there are 3 cases: *easy*, the exploit can be easily identified and reflected; *medium*, the exploit can be easily identified, but reflection is not trivial; *hard*, when identification and especially reflection are unlikely to be possible, e.g., if the connection is encrypted. We perfectly understand that precisely defining all possible vulnerabilities at this stage is difficult, but it's important to incorporate them during the design phase instead of adding some vulnerabilities at the end of the development)

### Flag Store 1, Vuln 1
Description...

* Difficulty: easy
* Discoverability: hard
* Patchability: medium

...

### Flag Store 1, Vuln M

...

### Flag Store N, Vuln 1

...

### Flag Store N, Vuln K


Patches
-------

[comment]: # (For each of the vulnerabilities reported in the previous section, outline a possible fix)

### Flag Store 1, Vuln 1

...

### Flag Store 1, Vuln M

...

### Flag Store N, Vuln 1

...

### Flag Store N, Vuln K


Work Packages
-------------

[comment]: # (Brief description of each work package)

### WP 1, Short Description

...

### WP N, Short Description


Timeline
--------

[comment]: # (A realistic timeline to complete the service and a mapping between team members and work packages, i.e., who is doing what)
