MD Challenge - Bash Skills Game

![CMD Challenge](https://example.com/screenshot.png)

## Background Context

CMD CHALLENGE is an exciting game that tests your Bash skills. It challenges you to solve tasks using the command line, with questions gradually increasing in complexity. Participating in this project is entirely optional, but it offers an opportunity to improve your command line skills!

## Requirements

### General

-   A README.md file, located at the root of the project folder, is mandatory for this project.
-   This project will be manually reviewed.
-   As you complete each task, the name of that task will turn green.
-   You are required to create a screenshot showing the completion of the required levels.
-   Push this screenshot to GitHub in either PNG or JPEG format.

### Specific

In addition to completing the project tasks and submitting the required screenshots to GitHub, you must demonstrate the use of the SFTP (Secure File Transfer Protocol) command-line tool to move your local screenshots to the sandbox environment. Follow these steps:

1.  Take screenshots of the completed levels as per the general requirements.
2.  Open a terminal or command prompt on your local machine.
3.  Use the SFTP command-line tool to establish a connection to the sandbox environment. You will need the hostname, username, and password provided for the sandbox environment.
4.  Once connected, navigate to the directory where you want to upload the screenshots.
5.  Use the SFTP `put` command to upload the screenshots from your local machine to the sandbox environment.
6.  Confirm that the screenshots have been successfully transferred by checking the sandbox directory.
7.  Proceed to push the screenshots to GitHub, as mentioned in the initial requirements.

## Usage of SFTP Command-line Tool

To transfer the screenshots to the sandbox environment using SFTP, follow these steps:

1.  Open a terminal or command prompt on your local machine.
2.  Use the following command to establish an SFTP connection:

cssCopy code

`sftp username@sandbox_hostname` 

Replace `username` with your sandbox username and `sandbox_hostname` with the provided hostname for the sandbox environment.

3.  Enter your password when prompted to authenticate the connection.
    
4.  Once connected, navigate to the destination directory on the sandbox environment where you want to upload the screenshots:
    

bashCopy code

`cd /path/to/destination/directory` 

5.  Use the `put` command to upload the screenshots from your local machine to the sandbox:

luaCopy code

`put /path/to/local/screenshot.png` 

Replace `/path/to/local/screenshot.png` with the actual path to your local screenshot.

6.  Repeat the `put` command for each screenshot you want to transfer.
    
7.  After uploading all the screenshots, you can check the sandbox directory to confirm the successful transfer.
    

## Manual QA Review

It is your responsibility to request a review for this project from a peer. If no peers are available for review, you can request a review from a TA or staff member.

Remember, this project is not mandatory, and it is meant for your practice and enjoyment. Have fun challenging your Bash skills in CMD Challenge!
