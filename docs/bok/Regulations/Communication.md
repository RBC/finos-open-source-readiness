---
title: Communications
tags: 
  - Legal (Role)
  - CIO/CTO (Role)
  - OSPO (Role)
  - Legal Risk
  - Contribution 
  - Policy
list_image: /img/bok/regs/communications.png 
---

<BoxOut title="Communications" image="/img/bok/regs/communications.png">

Regulated industries need to track communications internally and externally.  Keep in mind these broad principles about communication in regulated firms:

 - They are required to **maintain complete and accurate records of all communication**, including telephone conversations, emails, and instant messages, with customers and other parties.
 - These records must be **kept for a specified period of time**, typically at least five years, and should be easily accessible and retrievable for regulatory and legal purposes.
 - They must implement suitable technology to capture and store electronic communication data, and maintain appropriate security measures to **protect the integrity and confidentiality** of the records.
 - They must provide **regular training to staff** on the importance of accurately recording communications and ensure that all employees adhere to relevant laws, regulations, and industry standards.
 - Banks must establish clear policies and procedures for the retention and disposal of recorded communications, and must inform customers and other parties of the nature and extent of their recording practices.
 
</BoxOut>

## Intersection With Open Source

- Financial companies do define their retention policies when comes to record management, like how email communication, internal source code, internal chat systems (all involving possible counter parties) are applied to all firm business; some of these even surveiled in real time. However, such policies only apply to what is considered _firm business_. 

- Banking regulations around electronic communications are mainly aimed at broker-dealer relationships, preventing collusion and enforcing "information barriers" to prevent conflicts-of-interest.  They normally apply to tools like Zoom, Symphony, Email etc. and cover retention periods, supervision etc.

- Clearly, an open source contribution needs to adhere to these rules, even if it is not really the subject of them.

### Controls

- [Publication](../Activities/Level-3/Publication)
- [Surveillance](../Activities/Level-3/Surveillance)

## Relevant Regulations

### Market Abuse Regulation (MAR)

In order to prevent insider dealing and market manipulation, under the [European Union's Market Abuse Regulation (MAR)](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32014R0596&from=EN), firms must maintain effective systems and controls to detect, prevent, and report market abuse, and to keep records of all communications that are capable of leading to a transaction.

**Example:** The US has a similar regulation, [Securities and Exchange Commission's (SEC) Regulation Fair Disclosure (Reg FD)](https://en.wikipedia.org/wiki/Regulation_Fair_Disclosure).  In 2022 several major firms were fined under this regulation for using WhatsApp messenger, an un-monitored and unauthorized communications platform:

> The Securities and Exchange Commission announced $1.1 billion in fines and the Commodity Futures Trading Commission disclosed $710 million in penalties in separate statements Tuesday. Those levies -- against firms including Bank of America Corp., Citigroup Inc. and Goldman Sachs Group Inc. -- combined with JPMorgan Chase & Co.’s $200 million in fines from December, bring the total to $2.01 billion, making them the biggest penalties ever against US banks for record-keeping lapses. - [Wall Street Hit With $2 Billion of Fines in WhatsApp Probe, _Bloomberg_](https://www.bloomberg.com/news/articles/2022-09-27/wall-street-whatsapp-probe-poised-to-result-in-historic-fine)

See also: 

- [Data Leakage Risk](../Risks/Data-Leakage-Risk).
