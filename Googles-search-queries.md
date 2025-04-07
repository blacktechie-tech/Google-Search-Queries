## REPORT ON THE CONSTRUCTION OF COMPLEX SEARCH QUERIES

## GOALS
1. DEFINE THE VARIOUS ONLINE TOOLS TO CONSTRUCT COMPLEX SEARCH QUERIES.
2. USING THE QUERIES TO PERFORM OSINT AND RETRIEVE SENSISTIVE INFORMATION.

   ## RESEARCH ON DORKGPT
  DorkGPT is an AI-powered tool designed to assist users in generating advanced search queries, commonly known as "Google dorks." These specialized search operators enable users to uncover specific information on the internet that might not be easily accessible through standard search methods. ​

Key Features of DorkGPT:

AI-Generated Google Dorks: Utilizes artificial intelligence to craft precise and effective search queries tailored to user input.​

Enhanced Search Precision: Aims to streamline the process of finding targeted information by automating the creation of complex search strings.​


User-Friendly Interface: Designed to be accessible, allowing users to input simple search terms and receive advanced queries in return.​

For example, a user seeking resumes of doctors might input a straightforward query, and DorkGPT would generate a specialized search string to locate such documents. ​
RecruitingDaily

While DorkGPT serves as a powerful tool for information retrieval, it's essential to use it responsibly and ethically, ensuring compliance with legal standards and respecting privacy considerations. 
 ## MODIFICATIONS AND SOLUTION TO SOME COMPLEX QUERIES
 
 ## Construct Complex search queries and perform queries on Google.
The selected target website is 'The Hacker News'
From the website, select an author of your choice who publishes articles regularly. Construct a search query to find all articles written by that author on a selected Advanced Persistent Threat (APT). Use at least three keywords and phrases related to the APT in your search query

 USING BASIC GOOGLE SEARCH OPERATORS :
- site: ```thehackersnews.com```
- site:```thehackersnews.com | Author : Ravie lakshmanan|```
- Types of APT : site:```thehackersnews.com "stuxnet" "Helix kitten" " Exfiltration" ```

```bash
 site:thehackersnews.com |ravie lakshamanan| "stuxnet" "Helix kitten" "Exfiltration".
```

 In this section, articles written about the selected APT and author was validated.

 ## Construct a search query to find articles about stalkerware designed for Android, published in 2022 and 2023
```bash
  site:thehackersnews.com |stalkerware andriod | 2022 & 2023.
```
  ---
Articles published in 2022 and 2023 were viewed with accuracy about Andriod stalkware
 
 
 ### Construct a search query to find articles about ransomware targeting the Middle East region, with a focus on Linux-based attacks. Find articles published within the last six months.
```bash
site:thehackersnews.com | ransomware targeting the middle East | " linus-based Attacks" after:2022-05-01 before:2022-11-01,
```
 ---
Validation on the articles about linus-based ransomeware targeting the middle east was justified.

### Construct a search query for all articles about security attacks on AWS cloud infrastructure, specifically targeting the IAM service, from September 2023 to March 2024
```bash
site:thehackersnews.com | security attack AWS cloud infrastructure IAM service | after:2023-09-01 before:2024-03-31.
```
 ---
I can confirm the availability of articles discussing security attacks targeting the AWS Identity and Access Management (IAM) service published between September 2023 and March 2024.


### Construct a search query to find articles discussing phishing and spear phishing campaigns led by cyber adversaries in Iran. Ensure that the articles specifically discuss campaigns that used documents to lure victims

```bash
site:thehackersnews.com filetpye:pdf | phishing spear phishing campaign cyber adversaries Iran| "document lure victims" .
```
 ---
The Document used to lure victims in the articles discussing phishing and spear phising campaign led by the Iranian cyber adversaries were accessible.

## Construct a search query to find articles discussing zero day vulnerabilities on Cisco switches and Cisco firewalls
```bash
site:thehackersnews|  zero day vulnerabilities on Cisco switches and Cisco firewalls| after:2022 before:2023
```
---
The CIsco network devices and zero day vulnerability articles were accessible on the websites.

