# Glossary

If you are new to Copernica and e-mailmarketing you might encounter many 
new terms in our documentation and software. This page is meant to explain 
some of the most important terms to help you get started. Some terms 
also contain a link to our documentation to provide you with more information.


| Term                                                 | Description                                                                                                                                                                       |
|------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [API](./apis)                                        | Application Programming Interface: A set of standard protocols to get access to the data of an application. See REST and SOAP.                                                    |
| CNAME record                                         | Canonical Name Record: Used to give a domain an alias. This way you can create a website with Copernica on your own domainname, for example.                                      |
| [DKIM](./dkim)                                       | Domain Keys Identified Mail: Used to digitally sign your emails in the header of the email. Used to verify your identity.                                                         |
| [DMARC](./dmarc)                                     | Domain-based Message Authentication, Reporting and Conformance: A policy in the DNS record. It specifies how to handle emails where DKIM or SPF records are missing or incorrect. |
| [DNS](./dns)                                         | Domain Name Server: The system that translates domains to IP addresses.                                                                                                            |
| HTTP                                                 | Hypertext Transfer Protocol: Standard internetprotocol for sending information. Does not encrypt.                                                                                 |
| HTTPS                                                | Hypertext Transfer Protocol Secure: Safer and newer version of HTTP. Uses SSL for encryption.                                                                                     |
| [MailerQ](https://www.mailerq.com/)                  | Copernica's high performance mail transfer agent.                                                                                                                                 |
| [Marketing Suite](https://ms.copernica.com/)         | Copernica's newest user-friendly marketing software. Newer version of precedessor Publisher.                                                                                      |
| MTA                                                  | Mail Transfer Agent: Send the emails themselves. Copernica uses their own software [MailerQ](www.mailerq.com).                                                                    |
| [MX](./mx)                                           | Mail eXchange record: Contains the name of the computer that handles email traffic for the domain. This will refer to Copernica in your case to handle bounces.                   |
| [Publisher](https://publisher.copernica.com/)        | Copernica's older marketing software. Precedessor of the newer user-friendly Marketing Suite.                                                                                     |
| [Responsive Email](https://www.responsiveemail.com/) | Copernica's internal API to turn JSON into emails that work on every device.                                                                                                      |
| [REST](rest-api)                                     | Representational State Transfer: An API for Copernica data.                                                                                                                       |
| [Sender domains](./sender-domains)                   | Domain to email with from Copernica. Results in a set of DNS records (MX, DKIM, SPF and DMARC) to put on your server so we can make emailing easy!                                |
| SMTP                                                 | Simple Mail Transfer Protocol: Standardprotocol for sending e-mails.                                                                                                              |
| [SMTPeter](https://www.smtpeter.com/)                | A Copernica product used for sending pre-made emails.                                                                                                                             |
| [SOAP](soap-api-documentation)                       | Simple Object Access Protocol: An API for Copernica data. We recommend using the newer REST API.                                                                                  |
| [SPF](./spf)                                         | Sender Policy Framework: Ensures that Copernica is allowed to send email from your address in this case.                                                                          |
                                                                                                                                                                                                                                              
## More information                                                                                                                                                                                                                        

* [Quick start](./quick-start-guide)
* [Setting up a sender domain](./quick-sender-domain-guide)
* [Database management](./quick-database-guide)
* [Your first mailing](./quick-mailing-guide)
