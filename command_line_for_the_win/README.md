# Project README - Using SFTP for File Transfer

This README provides a step-by-step guide on how to use the SFTP (Secure File Transfer Protocol) command-line tool to transfer files in the context of the project.

## Prerequisites

- Access to the CMD CHALLENGE game for completing tasks.
- An SFTP client installed on my local machine.
- Credentials (hostname, username, and password) for the sandbox environment provided for this project.

## Steps to Use SFTP for File Transfer

### 1. Completing Project Tasks and Taking Screenshots

- Play the CMD CHALLENGE game and complete the required tasks.
- Take screenshots of the completed tasks and save them in a local directory in PNG format.

### 2. Connect to the Sandbox Environment

- Open CMD on the local machine.
- Use the SFTP command-line tool to establish a connection to the sandbox environment. Replace `[hostname]`, `[username]`, and `[password]` with my provided credentials:


### 3. Navigate to the Target Directory

- Once connected, navigate to the directory on the sandbox environment where to upload the screenshots (command_line_for_the_wi).

### 4. Upload Screenshots to Sandbox

- Use the `put` command to upload the screenshots from the local machine to the sandbox environment.
- Confirm the successful transfer by checking the sandbox directory using the `ls` command in the SFTP session.

### 5. Push Screenshots to GitHub

- Push the uploaded screenshots to GitHub repository, ensuring they are placed in the appropriate directory.
