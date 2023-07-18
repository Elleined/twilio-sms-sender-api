# twilio-sms-sender
Sending text message using spring boot with twilio

# Check this sites for more comprehensive tutorial 
  - https://www.tutorialspoint.com/spring_boot/spring_boot_twilio.htm
  - https://www.javadream.in/twilio-java-api-twilio-send-sms-with-spring-boot/
  - https://youtu.be/lJxjTLU9pGs

# How to run this project 
  - Supply the appropriate values specified in application.properties file and everything should works fine
  - And hit the this endpoint with request body of
  ```
    POST http://localhost:{postNumber}/twillio/sendSMS
    Content-Type: application/json

    {
      "receiverNumber": "+639#######",
      "body": "Your message"
    }
  ```
  // Use the appropriate country code. For me in Philippines its +63
# How many sms can you send using twilio 
 - Twilio Trail account only last for 45 days
 - After this free Trail credit reaches to zero that will be your limit
   
![image](https://github.com/Elleined/twilio-sms-sender/assets/111877930/136b2a27-5769-4e85-829c-9b2f0ad2fee0)

  
