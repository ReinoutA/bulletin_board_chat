# Secure and Privacy-Preserving Message Exchange Protocol

This repository implements a secure and privacy-friendly asynchronous message transmission protocol using a public bulletin board. The protocol ensures that individual send or receive events are unlinkable, thereby protecting both the content and metadata of the communication. The bulletin board can be hosted on a public cloud without additional risk, and the protocol remains efficient and scalable.


## **Key Features**
- *Unlinkability:* The protocol ensures that individual send and receive events cannot be linked, protecting users' privacy.
- *Scalability:* The central bulletin board can be scaled and distributed based on load.
- *Asynchronous Communication:* Messages can be sent even if the recipient is offline.
- *Social Graph Protection:* The protocol hides the social graph, preventing adversaries from reconstructing who is communicating with whom.
- *No Centralized Server Required:* Although a centralized bulletin board is used, it does not expose metadata, making the approach practical for large-scale adoption.

## **Use Cases**
- Journalists and Whistleblowers: Enables secure and anonymous communication in hostile environments without revealing contact information.
- Privacy-Preserving Messaging Apps: Can be integrated into applications like WhatsApp or Signal to enhance privacy by hiding metadata.

## **References**

This implementation is heavily based on the following article:

```plaintext
J.-H. Hoepman, "Privately (and Unlinkably) Exchanging Messages Using a Public Bulletin Board".
