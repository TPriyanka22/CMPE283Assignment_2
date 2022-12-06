# CMPE283Assignment_2

## Steps to reproduces the development steps:

1. Assignment is done by me

2. Please find the steps to recreate the development steps:

● Create a free tier account in the Google Cloud Platform to make use of the services.

● Create a VM through UI or fill in the information like Name, InstanceId, Zone, machine type, and CPU Platform and click on the Equivalent command line button (present at the bottom of the page), cloud shell will open with the information filled similar to the screenshot below. Below are the details that were chosen for this assignment:

Name: cmpe283-instance

Zone: us-central1-b

Machine Type: n2-standard-8

CPU Platform: Intel Cascade Lake

Boot disk : 100GB

● Add extra capabilities as per the requirement, here add enable nested virtualization before creating the instance.

<img width="1438" alt="Screenshot 2022-12-04 at 1 57 50 AM" src="https://user-images.githubusercontent.com/111544172/205783070-0ae80660-94f6-4c25-9f8f-ee921c7b2fa8.png">

● Click on the SSH on the newly created instance like below:

<img width="1438" alt="Screenshot 2022-12-04 at 2 06 42 AM" src="https://user-images.githubusercontent.com/111544172/205786523-e1202c8a-31a9-489f-920b-2fa27e198cf4.png">

● To check the configuration use the command - 'df -h'

<img width="897" alt="Screenshot 2022-12-04 at 2 17 05 AM" src="https://user-images.githubusercontent.com/111544172/205786819-c64cc9b0-1b69-4618-bb28-2456f34b316e.png">


● generate the public key by using the command 'ssh-keygen'

<img width="892" alt="Screenshot 2022-12-04 at 2 56 36 AM" src="https://user-images.githubusercontent.com/111544172/205809044-5259752b-7c5e-4b22-b5f3-43e36657a75d.png">

● Get the public key and add in the github account where linux code has been forked.

<img width="892" alt="Screenshot 2022-12-04 at 3 13 00 AM" src="https://user-images.githubusercontent.com/111544172/205809842-6b9efa15-cdd2-4eb9-b29a-70e0f58a27ee.png">


● Clone the repository here and 



