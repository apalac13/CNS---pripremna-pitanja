## Pripremna pitanja

1. What is the _Address Resolution Protocol (ARP)_, and what is its role in a network?
    - [ARP is a Data Link Layer protocol because it only operates on the local area network or point-to-point link that a host is connected to. The purpose of ARP is to resolve addresses by finding the MAC address that corresponds to an IP address.]
  
2. What is a _Man-in-the-Middle (MitM)_ attack, and how does ARP spoofing enable it?
   - [A Man-in-the-Middle (MitM) attack is where an attacker intercepts the communication between two parties and secretly alters the messages exchanged between them without their knowledge. ARP spoofing is a technique used by attackers to carry out MitM attacks on local networks by sending fake ARP messages to the victim's computer, pretending to be a legitimate device, and intercepting and modifying the communication between the victim's computer and the legitimate device.]

3. How does an attacker use ARP spoofing to intercept network traffic?
   - [An attacker can use ARP spoofing to intercept network traffic by sending fake ARP messages to the victim's computer, pretending to be a legitimate device on the network, typically the default gateway. These fake ARP messages contain a spoofed MAC address, which maps to the attacker's own device instead of the legitimate device.]
  
4. How is the _cookie_ used to derive the encryption/decryption key?
   - [In cookie-based encryption, a website's server encrypts sensitive data using a unique encryption key and then stores the encrypted data in a cookie on the user's computer. When the user sends a request to the website's server, the server includes the encrypted data and a session ID in the response. The user's browser then sends the cookie containing the encrypted data and session ID back to the server with subsequent requests, and the server uses the session ID to retrieve the corresponding encryption key from its database and decrypt the data in the cookie.]

5. What REST API request do you need to send to the _crypto oracle_ the secret cookie?
   - [GET /arp/cookie]
  
6. How do you obtain the authentication token?
   - [From crypto oracle server.]
  
7. How do you use the authentication token to obtain the cookie?
   - [To obtain the cookie, you would first need to authenticate the user and generate an authentication token. Then, you can use the authentication token to generate the cookie and send it back to the user's browser. Once the browser has stored the cookie, you can retrieve it from the browser with each subsequent request.]

8. What encryption mode is used to encrypt the challenge in this lab?
   - [AES-CBC]

9. What tool can you use to capture network traffic on a local network interface?
    - [tcpdump]
