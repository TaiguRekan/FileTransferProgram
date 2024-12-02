# FileTransferProgram
This project is a secure file transfer application that uses AES and DES for encryption and RSA for digital signatures. It ensures data integrity and authenticity during transmission. The user-friendly GUI allows users to select files, choose encryption methods, and manage server connections, all while logging key actions for reference.
# File Transfer and Cryptographic Signature Manager

## Description

This project is a secure file transfer application designed to ensure the confidentiality and integrity of files during transmission. It incorporates symmetric encryption algorithms (AES and DES) and digital signature technology (RSA) to protect data and verify authenticity, making it a robust solution for secure file sharing.

## Features

- **File Encryption**: Utilizes AES and DES algorithms to encrypt files before transmission, ensuring data privacy.
- **Digital Signatures**: Implements RSA for creating and verifying digital signatures, enabling users to verify the authenticity of received files.
- **User-Friendly Interface**: A graphical user interface (GUI) allows users to easily input server IPs, select files for transfer, and choose encryption and signing algorithms.
- **Logging**: The application logs critical operations such as server status and file transfer events for user reference and debugging.
- **Cross-Platform Compatibility**: Built with Java, this application can run on any platform supporting Java Runtime Environment (JRE).

## Getting Started

To get started with this project, follow these instructions:

### Prerequisites

- Java Development Kit (JDK) 8 or higher
- IDE (e.g., IntelliJ IDEA, Eclipse) or a text editor
- Maven (optional, if you're using it for dependency management)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TaiguRekan/FileTransferProgram
