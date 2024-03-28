### Haren Chowdary Doppalapudi | hd337

QR Code Generator
=================

Assignment Summary
-------------------

With the help of Python and Docker, this project creates a QR code generator that redirects the user to the GitHub homepage when scanned with the camera. 

Instructions
---------------

1.  Clone the Repository.

    `git clone https://github.com/haren0612/Homework7`
    
2.  Copy `.env.sample` file to `.env` file.

3.   Open the project directory and run the following command to create the Docker container.

    `docker build -t qr-code-generator .`

4.  Once the image has been created, launch the container using

    `docker run --name qr-generator -d qr-code-generator`

### Logging

bellow is the scrrenshot of log message:

![Log message](./log_screenshot.png)    
    
### QR Code
Scanning the QR code below will redirectthe user to the `https://github.com/haren0612/`.

![QR Code](qrcode/qr_code_20240328172135.png)


