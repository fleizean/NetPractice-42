<h1 style="text-align:center">NetPractice Helper</h1>

## Guidance
- [What is NetPractice](#whatis?)
  - [TCP](#TCP)
  - [How To Work](#How?) 
  - [IP's](#Ip's)
  - [Subnet Mask](#Subnet)
- [Components](#Components)
  - [Host](#Host)
  - [Switch](#Switch)
  - [Router](#Router)
  - [Internet](#Internet)
- [Solutions](#solutions)

## What is?
If we look at the project PDF, we can see the following statement. **This project is a general practical exercise to let you discover networking**. So we can move on to exploring the world of the network.

### TCP
</br>
<p align="center">
  <kbd><img src="img/img_others/howTCPworks.png" height=250 alt="mask"></kbd>
</p>
</br>

TCP **(Transmission Control Protocol)**, it is a protocol that enables communication between computers to be carried out in small packets and without loss. The most important part of this protocol is to receive or send data as a whole. Protocols and data records of terms we come across in daily life such as HTTP, HTTPS, POP3, SSH, SMTP, TELNET and FTP are made in TCP form.

### How?

</br>
<p align="center">
  <kbd><img src="img/img_others/understandingTCP.png" height=350 alt="mask"></kbd>
</p>
</br>

The working logic of the TCP protocol can be examined under three headings. In the first step, a connection **request** is sent to the destination. In the second stage, the connection is confirmed and **data transfer begins.** In the third stage, the connection is terminated by sending it to the parties where the **data transfer is completed.** The realization of these three stages is defined as the **State** process.

In TCP, some intermediate situations also occur for the realization of these three main stages. These intermediate states are listed as follows:

#### LISTEN
The state in which a TCP connection request is expected by the server. It is called the listening mode.

#### SYN-SENT
After sending a TCP connection request to the other party, it is called the situation where the connection request from the other party is expected to be answered.

#### SYN-RECEIVED
If the server responds with the SYN-ACK flag to the connection request made with the SYN flag, it is called the next wait state.

#### ESTABLISHED
It is the state where the data transfer is made after the connection setup is finished.

#### FIN-WAIT-1
It is the wait state of the server and its environment.

#### FIN-WAIT-2
FIN_WAIT_2 seems to occur when the server has an active connection with a client and wants to shut down the TCP connection.

#### CLOSE-WAIT
It is the state in which a connection closure request is expected by the server and the client.

#### CLOSING
After an ACK flag is sent to the other party to terminate the connection is called the wait for the connection to end.

#### LAST-ACK
The state where the ACK flag is expected.

#### TIME-WAIT
It is a standby state.

#### CLOSED
It is called the state where TCP data is completely exhausted.

### Ip's

### Subnet

## Components

### Host

### Switch

### Router

### Internet

## Solutions
