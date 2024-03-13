# MicrosoftSentinel-Playbook
This repository will host the playbooks to automate certain tasks.

#Overview
The Logic App is designed to streamline incident response and investigation processes with a suite of functions. It begins by generating an Incident Summary, providing a concise overview of the incident at hand. Investigation Guidance offers structured steps to follow during the investigative process. The app identifies and lists Involved Entities such as users and devices implicated in the incident. Authentication Methods are analyzed and reported to understand how access was gained. IP Enrichment provides additional context by enhancing IP addresses related to the incident, while Domain Enrichment does the same for domain names. Filehash Enrichment augments understanding by providing extra details about file hashes involved. Host Details offers comprehensive information on hosts involved, such as servers and endpoints. Lastly, Similar Incidents highlight past incidents with similarities for contextual analysis, aiding in effective response and mitigation strategies.

## Pre-deployment Instructions

Prior to beginning the installation process, it's crucial to confirm that you have met the following prerequisites:
1. The user that will deploy this Logic app need to have a Contributor Role.
2. You enabled the Security Copilot license on your tenant
3. The user authenticated within the CoPilot logic app action and has permission to send emails.
4. Define the email you want the daily logic app to be sent too.
