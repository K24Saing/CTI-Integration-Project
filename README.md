# CTI-Integration-Project

## Objective

The CTI Integration Project is aimed to set up and configure a threat intelligence feed to analyze current threats by using an Open Threat Exchange (OTX) known as AlienVault into the OpenCTI platform for analysis. By setting up the OpenCTI platform connected with AlienVault, I was able to understand the current threat landscape facing different sectors and governments. This threat feed contains various amounts of information such as the top vulnerabilities, indicators of compromise, malware, and reported incidents that are ongoing events. With this threat intelligence information, I'm able to further enrich my investigations and analysis capabilities.

### Skills Learned

- Advanced understanding of threat intelligence feeds and utilizing open threat exchanges.
- Learned how to configure my own CTI platform and connect it to Open Threat Exchanges via AlienVault and GitHub repositories.
- Analyze the current threat landscape of different industries and governments being affected by cyber threats.
- Dive deep into the top vulnerabilities and indicators of compromises to look after when performing investigative analysis of environment.
- Gain knowledge of the various threat actor groups and their tactics against different industries.


### Tools Used

- Continuous Threat Intelligence (CTI) platform // OpenCTI
- Threat Intelligence Feed // OTX AlienVault
- Virtual environment for CTI platform. // VMWare, Ubuntu
- Public Repository Configuration Codes // GitHub

## Steps

1. Configure a Virtual Machine using Ubuntu Linux operating system for the OpenCTI platform
2. Download a Docker to import the OpenCTI application by following steps on the GitHub page.<br>
<br>![OpenCTI (1) Docker Download](https://github.com/user-attachments/assets/86d70bbf-7c8d-4b71-9e1d-2798182239f1)<br>
![OpenCTI (2) Repository](https://github.com/user-attachments/assets/9721d485-adc9-4c1d-a903-35ecb8bf15d5)<br>
<br>
3. While in the Docker directory, I navigated to the docker-compose file to start configuring the application with the appropriate login information and IP address of the virtual machine used to host the OpenCTI application.<br>
4. Started the Docker service, and directed to the OTX AlienVault website where the threat intelligence feed is sourced from. I copied the OTX Key used for AlienVault and pasted it into the docker-compose.yml file.<br>

<br>![OpenCTI (5) OTX Key](https://github.com/user-attachments/assets/dcdb8b0e-3a65-44bc-ae5f-953e1fca8c25)<br>

<br>![OpenCTI Configuration (7) YAML](https://github.com/user-attachments/assets/aee2cdef-e2a5-4927-baad-22d24ea10e64)<br>

<br>![OpenCTI Configuration (8) YAML](https://github.com/user-attachments/assets/273f0e0a-f4dc-48db-8a6f-cc0c4a328b25)<br>

5. After configuring the Alien Vault threat intelligence feed key to my OpenCTI threat intelligence platform, it was now ready to start downloading the necessary connecting files to integrate into the OpenCTI application. I restarted the docker service so that it will now start pulling the threat feeds from the AlienVault website.<br>

<br>![OpenCTI Digests (8)](https://github.com/user-attachments/assets/bfa3753e-2e62-4aa0-a394-8d51e2a11b33)<br>

6. I navigated to the IP address of my virtual machine that hosted the OpenCTI application, logged in with the configured information, and started seeing threat telemetry being feeded into the application from the AlienVault threat intelligence source. By understanding how to connect this threat feed to the OpenCTI application, I was able to gain a lot of technical knowledge on including more threat feeds for more enriched data if possible. <br>
<br>![OpenCTI final page (1)](https://github.com/user-attachments/assets/b0d996dc-5452-4226-9cff-bfd3672b382a)<br>

7. With this threat intelligence telemetry being generated into my OpenCTI application, I was able to look deep into the top threat actor groups and active malware being used, vulnerabilities facing different industries and governments, the top indicators of compromises to look out for, and the latest reports and victims facing the current threat landscape today.

