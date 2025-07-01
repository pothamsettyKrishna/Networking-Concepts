# OSI Model

## DNS Resolution

DNS (Domain Name System) is essentially the internet's phonebook.

It translates human-friendly domain names (like google.com) into the numerical IP addresses that computers use to locate and connect to website.

## TCP handshake

The TCP handshake, also know as three-way handshake, is a process used in TCP/IP networks to establish a reliable connection between a client and a server.

## OSI Model

The OSI (Open Systems Interconnection) Model is like a step-by-step recipe or a set of rules that computers follow to communicate with each other over a network.

The OSI model breaks down the complex process of computer communication into 7 simpler, more manageable layers, each with a specific job.

## 7. Application Layer (What you interact with)

This is the closest layer to the user. It provides services for applications like web browsers, email clients, and file transfer programs to interact with the network. Think of HTTP for web Browse, SMTP for email, or FTP for file transfers.

## 6. Presentation Layer (Translator & Formatter)

This layer translates data between the application layer and the network format. It handles data encryption, decryption, compression, and ensures data is in a format that the receiving application can understand.

## 5. Session Layer (Starting and Ending Conversations)

This layer establishes, manages, and terminates communication sessions between applications. It ensures that the conversation stays open long enough to exchange data and then closes it to free up resources.

## 4. Transport Layer (Reliable Delivery)

This is the "heart" of the OSI model. It's responsible for reliable, end-to-end delivery of data. It breaks data into smaller segments, handles error checking, and ensures data arrives at the destination correctly and in the right order. TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are key protocols here.

## 3. Network Layer (Finding the Best Route)

This layer deals with logical addressing (like IP addresses) and routing. It determines the best path for data packets to travel across different networks, using devices like routers.

## 2. Data Link Layer (Local Delivery & Error Checking)

This layer handles the physical addressing (MAC addresses) within a local network segment. It also detects and corrects errors that might occur on the physical layer and organizes data into "frames."

## 1. Physical Layer (The Wires and Signals)

This is the most basic layer. It deals with the actual physical connection between devices, defining things like cables, connectors, voltage levels, and how raw binary data (0s and 1s) are transmitted over the physical medium (like Ethernet cables or Wi-Fi radio waves).
