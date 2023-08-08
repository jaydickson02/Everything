- **Description**: SSH is a cryptographic network protocol that provides a secure channel over an unsecured network. It's widely used for remote command-line login and remote command execution, but any network service can be secured with SSH.
- **How it Works**:
    - **Authentication**: SSH uses public-key cryptography to authenticate the remote computer and (optionally) the user accessing it. The client begins by sending its public key to the server. If the server recognizes the key, the client is authenticated.
    - **Encryption**: Once authenticated, SSH encrypts all data transmitted between the client and server using symmetric encryption, ensuring that the information cannot be intercepted and read by others.
    - **Data Integrity**: SSH also ensures the integrity of the transmitted data by using cryptographic hash functions. This ensures that the data is not tampered with during transmission.
    - **Channels**: SSH connections can be used to set up various "channels," logical pipes for communication that can carry shell access, file transfers, or other types of data. Examples include SFTP (SSH File Transfer Protocol) for secure file transfers.

#### Ports
- 22