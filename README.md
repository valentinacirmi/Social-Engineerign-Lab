# Social Engineering Lab

## Objective

Demonstrate how phishing attacks can be used to harvest credentials through cloned websites and analyze defensive measures that organizations and users can implement to reduce risk.

## Scope

This project was conducted in a controlled laboratory environment for educational purposes.

The objective was to understand the mechanics of phishing attacks, identify indicators of compromise and evaluate mitigation strategies.

## Tools Used

* Kali Linux
* Social-Engineer Toolkit (SET)

## Attack Scenario

A credential harvesting attack was simulated against a university virtual campus login page.

The target website was cloned using the Social-Engineer Toolkit (SET), generating a phishing page visually identical to the original login portal.

When a user submitted credentials through the cloned page, the information was captured and the victim was redirected to the legitimate website.

## Attack Workflow

1. Launch SET.
   
   ![setoolkit](screenshots/setoolkit.png)
   
2. Select Social Engineering Attacks.
   
   ![social_engineering_attacks](screenshots/social_engineering_attacks.png)
   
3. Select Website Attack Vectors.
   
   ![website_attack_vectors](screenshots/website_attack_vectors.png)
  
4. Select Credential Harvester Attack Method.
   
   ![harvester_attack_vectors](screenshots/harvester_attack_vectors.png)
   
5. Select Site Cloner.
    
   ![site_cloner](screenshots/site_cloner.png)
   
6. Configure target URL and attacker IP.
    
    ![site_cloner_data_input](screenshots/site_cloner_data_input.png)
    
7. Generate phishing page.
    
    ![cloned_site](screenshots/cloned_site.png)
    
8. Capture submitted credentials.
    
    ![credential_harvester](screenshots/credential_harvester.png)
    
9. Redirect victim to the legitimate website.
    
    ![site_comparison](screenshots/site_comparison.png)
    

## Security Risks

This type of attack exploits human behavior rather than technical vulnerabilities.

Common attack vectors include:

* Email phishing campaigns
* SMS phishing (smishing)
* Fake password reset requests
* Account verification messages
* Urgent security notifications

## Mitigation Strategies

### User Awareness

Users should verify:

* Domain names
* Sender identity
* HTTPS usage
* Unexpected login requests

### Multi-Factor Authentication (MFA)

Even if credentials are compromised, MFA can significantly reduce the likelihood of unauthorized access.

### Organizational Controls

Organizations should implement:

* Security awareness training
* Email filtering
* Web Application Firewalls (WAF)
* Domain monitoring
* Least privilege principles

## Key Takeaways

Phishing remains one of the most effective attack techniques because it targets human trust rather than software vulnerabilities.

Technical controls are important, but user awareness remains one of the strongest defenses against credential harvesting attacks.

## Disclaimer

This project was conducted exclusively in a controlled educational environment.

No unauthorized systems, users or organizations were targeted.
