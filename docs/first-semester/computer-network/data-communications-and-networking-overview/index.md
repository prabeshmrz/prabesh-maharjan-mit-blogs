# Data Communications and Networking Overview

A network is essentially a group of computers or other hardware components that have been physically or logically connected using specialized hardware and software to share information and work together. Similarly, networking refers to designing, implementing, and managing networks. Through networking we can achieve data sharing, communication, hardware and software sharing, internet access, etc.

## A Communications Model
This is a basic model where a sender uses a channel or medium to transmit an encrypted message, and the receiver decodes it and responds.

The components involved in basic communication model are shown in Figure~\ref{fig:bcm}. The process begins from the source which sends the messages. The original signal is encrypted and converted to transmittable signal, and is transmitted through any medium. This signal once received by the receiver decrypts it and converts back to original signal which is sent to destination. Key tasks involved in this process are signal generation, interfacing, message formatting, exchange management, routing, security, error detection and correction, syncronization, and network management.

## Protocol Architecture
Protocols are the collection of guidelines that control how computers communicate with one another. They are made to guarantee that data and messages transmitted from one computer to another do so securely and in the proper sequence. On the other side, protocol architecture is a network of connected protocols. Its purpose is to offer a foundation for networked computer communication. It typically includes three layers, i.e; Network access layer, Transport layer, and Application layer. ***Network layer*** handles exchange of data between end system and network, it provides destination address. ***Transport Layer*** is responsible to reliable data exchange independent of underlying hardware or applications used. ***Application Layer*** is where user initiates communication through various applications, e.g., email, file transfer.


## TCP/IP Protocol Architecture
All contemporary networking is built on the TCP/IP protocol architecture. It is
hierarchical protocol consisting multiple modules which each serves specific
functionality. It consists of 5 layers. They are:

  - **Physical Layer:**
    It is the channel or medium for the data transmission between devices in a network. It has the characteristics of transmission medium like signal levels and data rates.

  - **Network Layer:**
    It is responsible for the exchange of data between the end systems through a network. It encapsulates the IP datagram into transmittiable frames and also maps IP address to physical address.

  - **IP Layer:**
    The main responsibility of this layer is to ensure the packets routed through any network to reach the destination. It does so with the help of IP address.

  - **Transport Layer:**
    This layer is responsible for providing reliability and over all flow control of the data being sent through the network.

  - **Application Layer:**
    It is the topmost layer of TCP/IP layer. It handles high level protocols like http and allows user to communicate through interactive applications like web browsers, email clients.
