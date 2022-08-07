# Technical-Papper-On-OSI-Layers
## OSI Layer

 


## Introduction 

What Is the OSI Model ?

The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s.

## The OSI 7 Layers

We’ll describe OSI layers “top down” from the application layer that directly serves the end user, down to the physical layer.

7. Application Layer
   
 The application layer is used by end-user software such as web browsers and email clients. It provides protocols that allow software to send and receive information and present meaningful data to users.
Example like Hypertext Transfer Protocol (HTTP) , ile Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP).

6. Presentation Layer

 The presentation layer prepares data for the application layer. It defines how two devices should encode, encrypt, and compress data so it is received correctly on the other end. The presentation layer takes any data transmitted by the application layer and prepares it for transmission over the session layer.

5. Session Layer

The session layer creates communication channels, called sessions, between devices. It is responsible for opening sessions, ensuring they remain open and functional while data is being transferred, and closing them when communication ends. The session layer can also set checkpoints during a data transfer—if the session is interrupted, devices can resume data transfer from the last checkpoint.

4. Transport Layer

 
The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the session layer.

3. Network Layer
  
The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end. The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses

2. Data Link Layer

The data link layer establishes and terminates a connection between two physically-connected nodes on a network. This layer is composed of two parts—Logical Link Control (LLC), which identifies network protocols & , and Media Access Control (MAC) which uses MAC addresses to connect devices and define permissions to transmit and receive.

   1. Physical Layer

The physical layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s.

## Advantages of OSI Model

The OSI model helps users and operators of computer networks:
* Determine the required hardware and software to build their network.

* Understand and communicate the process followed by components communicating across a network. 

* Perform troubleshooting, by identifying which network layer is causing an issue and focusing efforts on that layer.

* It is a standard model in computer networking.

* Helps you to accelerate the evolution.

* Helps you to accelerate the evolution.

## Disadvantages of the OSI Model

Here are some cons/ drawbacks of using OSI Model:

* Fitting of protocols is a tedious task.

* You can only use it as a reference model.

* Doesn’t define any specific protocol.


* In the OSI network layer model, some services are duplicated in many layers such as the transport and data link layers

*
## Interaction Between OSI Model Layers

Information sent from a one computer application to another needs to pass through each of the OSI layers.

This is explained in the below-given example:

* Every layer within an OSI model communicates with the other two layers which are below it and its peer layer in some another networked computing system.

* The data link layer of the first system communicates with two layers, the network layer and the physical layer of the system. It also helps you to communicate with the data link layer of, the second system.


## Summary

* The OSI Model is a logical and conceptual model that defines network communication which is used by systems open to interconnection and communication with other systems.

*  In OSI model, layer should only be created where the definite levels of abstraction are needed.

* OSI layer helps you to understand communication over a network.

* In 1984, the OSI architecture was formally adopted by ISO as an international standard.




