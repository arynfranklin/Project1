# Project1
Cyber and Network Security Bootcamp Project #1

The purpose of this project is to use all of the knowledge and skills learned so far in the Cyber and Network Security Bootcamp. In this project, I configured an ELK server and installed Filebeat and Metricbeat. 


# Description of Deployment 
The following describes how to deploy the project and access the network:
1. Turn on all virtual machines
2. SSH into the Jump-Box-Provisioner 
3. Start the Ansible container and connect to it
4. SSH into DVWA-VM1 using the internal IP address, then exit.
5. In the Ansible container, SSH into the DVWA-VM2 using the internal IP address, then exit.
6. Still in the Ansible container, SSH into ELK-VM3 using the IP address
7. Navigate to http://[VM.IP]:5601. Use the public IP address of the ELK server that you created.
8. To confirm that the ELK stack was receiving logs. Navigate back to the Filebeat installation page on the ELK server GUI 
9. If the ELK stack was successfully receiving logs, you would have seen a confirmation
10. To verify that the Metricbeat installation works as expected, navigate to the Metricbeat installation page in the ELK server GUI. You would have seen a confirmation at the bottom of the page.
