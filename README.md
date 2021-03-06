---------------------------------------------------------------------
#   “HOME SECURITY ALERT MESSAGES TO         
#        (AWS) IoT”
#           $  
#       “READING DHT 11 SENSOR”                         
---------------------------------------------------------------------

# project-IoT-raspberry-pi-
## Temperature detected by sensor.
- Aware of IoT/project   
![](/images/rasospng.png)


>The block diagram of raspberry pi the interface of terminal. The code written in the terminal of the raspberry pi. The temperature sensor display the temp. On the terminal.


 ![](/images/block.png)      
## DHT11 Temperature and Humidity Sensor:
>This DHT11 Temperature and Humidity Sensor features a calibrated digital signal output with the temperature and humidity sensor capability. It is integrated with a high-performance 8-bit microcontroller. Its technology ensures the high reliability and excellent long-term stability.  This sensor includes a resistive element and a sensor for wet NTC temperature measuring devices. It has excellent quality, fast response, anti-interference ability and high performance.
#### Specification:
>•	Supply Voltage: +5 V   
•	Temperature range :0-50 °C error of ± 2 °C   
•	Humidity :20-90% RH ± 5% RH error

<img src="images/dht11.jpg" width=240 height=200>     

<img src="images/dht11b.png" width=400 height=350>

# GPIO PINS:
>The Raspberry Pi offers up its GPIO over a standard male header on the board. Over the years the header has expanded from 26 pins to 40 pins while maintaining the original pinout. If you're coming to the Raspberry Pi as an Arduino user, you're probably used to referencing pins with a single, unique number.


- Why is used GPIO?

>GPIO stands for General Purpose Input/Output. It's a standard interface used to connect microcontrollers to other electronic devices. For example, it can be used with sensors, diodes, displays, and System-on-Chip modules.

<img src="images/gpio.jpg" width=440 height=440>

 ### Bread board, GPIO pins, jumper wires, DHT11 Temperature and Humidity, Sensor and Resistor LEDs:
 <img src="images/bread.jpg" width="320" height="400">
 ### Connection raspberry pi though Laptop:
 >Connect your Ethernet cable to your computer and to the Raspberry Pi. Plug in the wall power adapter into the Raspberry Pi, and then plug it into the wall to turn the power on. Once the power is connected to the wall, the Raspberry Pi will be on.
 - Sharing Internet Over Ethernet:   
 >To share internet with multiple users over Ethernet, go to Network and Sharing Center. Then click on the WiFi network:

<img src="images/internet.png" width=410 height=420>

<img src="images/est.jpg" width=410 height=420>

### What is PuTTY and what is it used for?
>Like OpenSSH, PuTTY is a very versatile tool for remote access to another computer. It's probably used more often by people who want secure remote shell access to a UNIX or Linux system than for any other purpose, though that is only one of its many uses. PuTTY is more than just an SSH client

<img src="images/putty.png" width=410 height=420>

### Terminal of raspberry pi  

<img src="images/terminal.png" width=500 height=260>
### Project planning:
>1.	 I think the idea to sense the temperature and blink the LED though the codes.
2.	 Raspberry pi connect to pc and other instrument to support the temperature as well as LED blink.
3.	Plug the all the instrument and done the configuration.
4.	Install the software required to set up raspberry pi connection between computer.
5.	Than analysis the bugs.
6.	Than check the code working or not.

<img src="images/blockpl.jpg" width=330 height=320>

### Coding:
![](images/code.png)
### output of temperature sensor
![](images/tem.png)
### LED blink coding
![](images/light.png)
### LED blink 1
<img src="images/led1.jpg" width=340 height=400>
### LED blink 2
<img src="images/led2.jpg" width=340 height=200>

### Testing Techniques:
- check again GPIO pins
 ![](images/g.png)

## Raspberry by Motion sensor Pir Hc-Sr501

<img src="images/nomt.jpg" width=340 height=270>

- No Motion detected


<img src="images/mot.jpg" width=340 height=280>
- Motion detected

### Output of Sensor
<img src="images/sensor.png" width=390 height=380>

# Connection raspberry pi to AWS terminal
>--cli-input-json (string) Performs service operation based on the JSON string provided. The JSON string follows the format provided by --generate-cli-skeleton. If other arguments are provided on the command line, the CLI values will override the JSON-provided values. It is not possible to pass arbitrary binary values using a JSON-provided value as the string will be taken literally.
--generate-cli-skeleton (string) Prints a JSON skeleton to standard output without sending an API request. If provided with no value or the value input, prints a sample input JSON that can be used as an argument for --cli-input-json. If provided with the value output, it validates the command inputs and returns a sample output JSON for that command.

<img src="images/awscli.png" width=430 height=190>

<img src="images/awscliaw.png" width=590 height=400>




# Connection of AWS to raspberry
>boto3 is the Amazon Web Services (AWS) Software Development Kit (SDK) for Python, which allows Python developers to write software that makes use of services like Amazon S3 and Amazon EC2.
Boto3 is the name of the Python SDK for AWS. It allows you to directly create, update, and delete AWS resources from your Python scripts
Boto is a software development kit (SDK) designed to improve the use of the Python programming language in Amazon Web Services. ... Boto supports all current AWS cloud services, including Elastic Compute Cloud, DynamoDB, AWSConfig, CloudWatch and Simple Storage Service


<img src="images/bot.jpg" width=520 height=440>
B
- boto3 install

# Motion sensor to AWS send Message to Email(ses)
- What Is IAM?

>AWS Identity and Access Management (IAM) is a web service that helps you securely control access to AWS resources. You use IAM to control who is authenticated (signed in) and authorized (has permissions) to use resources.
When you first create an AWS account, you begin with a single sign-in identity that has complete access to all AWS services and resources in the account. This identity is called the AWS account root user and is accessed by signing in with the email address and password that you used to create the account. We strongly recommend that you do not use the root user for your everyday tasks, even the administrative ones.



<img src="images/run.png" width=590 height=120>
- run code

<img src="images/aws.png" width=700 height=280 >
- ses status

<img src="images/email.png" width=200 height=400>
- Email received





# work in progress.............
