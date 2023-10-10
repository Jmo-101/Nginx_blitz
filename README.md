# Nginx_blitz

<img width="550" alt="Screenshot 2023-10-09 at 9 17 54 PM" src="https://github.com/Jmo-101/Nginx_blitz/assets/138607757/1ab91216-8e8c-46bc-aeca-c98605e78e34">


## Scenario
You are in charge of deploying the new version of the application. The QA engineer will send 14,000 requests to the server. After the QA engineer tests your application, they will update you about the results.

# QA’s Activities:

The QA was in charge of stressing out the new application (URL Shortener) I had deployed. The QA sent 14,000 requests to our URL shortener to see if the application was capable of holding that much traffic.

## Stress Test:

During the stress test, I was monitoring the application and noticed that the CPU for the application was being pushed to its max. This gave me an idea that the strength of the instance was not enough for a large amount of traffic.

![Screenshot 2023-10-04 at 7 20 08 PM](https://github.com/Jmo-101/Nginx_blitz/assets/138607757/4f7ed720-da2c-46fa-bc6b-1c98cc8eda10)

## Solution:

My initial thought during this stress test was to use Nginx as a load balancer and direct traffic to another instance that has the URL shortener. In the end, I just deployed the application in a stronger instance to see if it could manage the amount of stress.
