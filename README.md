# SQS-Research
SQS Research for the AWS Developer Certification test prep.

https://dzone.com/articles/producer-consumer-pattern

## Long polling v Short Polling

**Long polling** overall is the better option as it pings the server less. Think of it like Instagram when you continuously scroll it will constantly update and refresh and continuously relay the message and communicate with the server. 

**Short polling** would be hitting F5 on a website. The reason this is slightly less efficient is if it fails it needs to continuously ping the server and ultimatley cost the producer more in the long run. 



