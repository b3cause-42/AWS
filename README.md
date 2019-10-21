# AWS
A virtual environment hosted in AWS. Meant to be an elastic, system with dynamic and randomized vulnerable images for practicing penetration testing.


The goal specs of this range are as follows.

1) Be accessible over public internet.
- Hosting on AWS/GC/AzureC

2) Be accessible behind private firewalls.
-Hosting on AWS GovCloud? or other equivalent.

3) Be capable of hosting up to 100 users at a time.
-Build in Load Balancers to manage traffic
-Use RDS service to trivialize user account management

4) Scale to the current number of users.
- Elasitcize the environment to allow for automatic growth

5) Automatic start up & shutdown with in certain hours.
- Set down time schedules

6) Identity & Access Management for user authentication.
- Use RDS service to trivialize user account management
- Optionally use a PostGRESQL or NoSQL instance to manage/hold the user information

7) Restrict Access to the network & VPCs based on IP ranges.
- User Security Group Rules
- Can Security Groups be Codified?

8) Elastically scale out instances based on user presence.
- Elasitcize the environment to allow for automatic growth

9) Track user progress.
- Use RDS service to trivialize user account management
- Optionally use a PostGRESQL or NoSQL instance to manage/hold the user information

10) Randomize certain parts of each instance to allow for constant variety & non repetition.
- Need to work on how this will happen
- Possibly Ansible or Chef?

11) Generate storylines for routes.
- Need to work on how this will happen
- Semantic Generation?
- Relation Topic Generation?
