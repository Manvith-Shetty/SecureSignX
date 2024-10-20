# Secure SignX

<h4 align="center">
  <a href="https://secure-sign-x.vercel.app/">Click here to visit Secure SignX Website</a>
</h4>

<br />

![SecureSignX](https://github.com/user-attachments/assets/2dbd2c6f-e090-473e-b572-3cf3a8df31e4)

<br />

🧪 Secure SignX is a decentralized compliance and audit trail system for managing document Attestations via Sign Protocol, with Secure communication through XMTP and streamlined interactions using a MessageKit Bot

Secure SignX involves two major components

**Sign Protocol**

Currently, the Secure SignX Attestation Schema is deployed on **Base Sepolia Testnet**

[SecureSignx Sign Protocol Schema](https://testnet-scan.sign.global/schema/onchain_evm_84532_0x22c)

Workflow:

1. The employee should connect his wallet and then needs to upload the legal Document.
   
2. Then the attestation to any legal document can be created only by the Compliance Officer/Auditor.

3. Then the manager can review the attested documents.


You can view the **Attestations created on Sign Protocol** from here (https://testnet-scan.sign.global/schema/onchain_evm_84532_0x22c)

<br />

![sign protocol schema](https://github.com/user-attachments/assets/0845be75-e2a0-48d1-9e8a-1ccd03973d94)

<br />

<br />

The second major component here is **XMTP Protocol**

**XMTP (Extensible Message Transport Protocol)** is used to send real-time notifications to relevant users about document submissions, attestations, and status updates. The system automatically sends notifications to the Manager, Compliance Officer, and Submitter based on the following events:

1. *Document Submission*: When a document is submitted, the bot sends the submission details, including the document name and IPFS CID, to the assigned Compliance Officer for review.
   
2. *Attestation Completion*: Once an attestation is made, real-time updates are sent: <br />
       - Submitter receives a message confirming their document's attestation and status. <br />
       - Manager receives a detailed attestation report containing the document name, IPFS CID, submitter, attestor, and compliance status. <br />
       - Compliance Officer is updated on any changes in document status or approval. <br />

A **Compliance Bot** built using **MessageKit** assists users based on their roles: **Manager**, **Compliance Officer**, and **User**. 

The bot is deployed and can be interacted with at the address: *0x9223a195cbaC6D5411367e7f316F900670a11d77*.

To see available commands and functionality, simply type **"help"** in the conversation with the bot through **XMTP**.

<br />

1. **Compliance Officer**
   
![Compliance Bot](https://github.com/user-attachments/assets/477d95f5-53a4-4609-b2d5-c77e7b84dac9)

2. **Manager**

![Manager Report](https://github.com/user-attachments/assets/48b07db1-b548-463c-8d2d-323a4d8bab2c)

<br />

## For Testing the app 

1. Visit [https://secure-sign-x.vercel.app/](https://secure-sign-x.vercel.app/) and click on the connect wallet button, then visit the Dashboard.
   
2. If you are an employee upload your legal document like NDA.
