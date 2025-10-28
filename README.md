## 0day-industry-awesome

The digital arms industry operates within the realms of both undisclosed (0-day) and publicly known (N-day) vulnerabilities, along with their corresponding exploit techniques. These digital arms are intangible weapons, structured in ways that can be challenging for people to grasp. Even experienced security professionals, ike security engineers, analysts, and CISOs, often find themselves entangled in misconceptions. What defines a bug? How does an exploitable bug differ? What exactly is a vulnerability, and what constitutes an exploit? What is an exploitation framework, and how do various exploit techniques fit into the picture? What distinguishes a weaponized exploit from a weaponized framework, package, or bundle? How are these concepts interconnected? During the period when HardenedLinux had a full-time maintainer (2015-2020), we dedicated ourselves to combatting digital arms through open source methodologies and along with engineered some fields of system security during HardenedVault. The asymmetry of information between attackers and defenders is striking. We've journeyed across multiple continents, and wherever we go, identifying oneself as part of the digital arms sector attracts eager business partnerships. In contrast, when discussing system security defenses, essentially positioning yourself as a shield builder, you may encounter dismissive reactions that convey sentiments like, “F* off, don’t waste my time!”

We frequently receive feedback reflecting confusion around radical threat models. Many individuals, driven by diverse motivations, dismiss the notion of confronting "The Desert of the Real" as futile or deny the desert's existence directly. However, we must ultimately face this reality. For defenders, comprehending weaponized exploits and the dynamics of the 0-day industry is essential for constructing effective cyber bunker. From the 0ldsk00l hacker mantra of "Hacking for fun and profit" to the inevitable reality of "This is cyber, sir!" in the age of cyber warfare, understanding these elements is crucial for navigating today’s complex landscape. This document will list the prices in the 0-day market because money is an easy language to both offensive and defensive sides. Any PR/contributions are welcomed!

## 0-day vendors

| Vendor        | Base                            | Last Updated Date  | Active status | Product                | SLA      | Price|
|:-------------:|:-------------------------------:|:------------------:|:-------------:|:----------------------:|:--------:|:----:| 
| Intellexa     | North Macedonia/Israel/Hungary  | 2023?              | ???           | Spyware package with Android/iOS 0-day exploits| 12-month | €8,000,000 | 
| [Operation Zero](https://opzero.ru/en/prices/)| Russia    | 2025               | Active        | 0-day | N/A | varies |
| [NSO](https://www.nsogroup.com/)     | Israel/US  | [Oct 2025](https://techcrunch.com/2025/10/10/spyware-maker-nso-group-confirms-acquisition-by-us-investors/) | Active           | Spyware package with Android/iOS 0-day exploits| ??? | unknown mininal package up to 55 million |
| Quadream | Israel | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |
| [Advanced Security Solution](https://advance-sec.com/#bounty)| UAE                 | 2025               | Active        | 0-day | N/A | varies |
| [Cellebrite](https://cellebrite.com/en/home/) | Israel | 2025        | Active         | Forensics with 0-day exploits | ??? | $10k-$300k |
| [Memento Labs (formerly Hacking Team)](https://mem3nt0.com/) | Italy | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |
| Paragon Solutions | Israel | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |
| [RCS Labs](https://rcslab.it/) | Italy | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |
| Vilicius Holding (formerly FinFisher) | Germany | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |
| Saito Tech (formerly Candiru) | Israel | 2025        | Active         | Spyware package with 0-day exploits | ??? | varies |



### Operation Zero
![1](https://github.com/hardenedlinux/0day-industry-awesome/blob/master/pics/opzero2025.png)

### Advanced Security Solution
![2](https://github.com/hardenedlinux/0day-industry-awesome/blob/master/pics/advsec2025.png)

## Bug bounty

### [Google VRP](https://bughunters.google.com/about/rules/android-friends/6171833274204160/android-and-google-devices-security-reward-program-rules)
| Description        | Maximum Reward  |
|:------------------:|:---------------:|
| Pixel Titan M with Persistence, Zero click | 	Up to $1,000,000|
|Pixel Titan M without Persistence, Zero click| 	Up to $500,000|
|Local App to Pixel Titan M without Persistence| 	Up to $300,000|
|Secure Element| 	Up to $250,000|
|Trusted Execution Environment| 	Up to $250,000|
|Kernel| 	Up to $250,000|
|Privileged Process| 	Up to $100,000 |

### [Apple Security Bounty](https://security.apple.com/blog/apple-security-bounty-evolved/)
![3](https://github.com/hardenedlinux/0day-industry-awesome/blob/master/pics/apple202511.png)

## Pwn2Own
In the mobile phone category of [Pwn2Own Ireland 2025](https://www.zerodayinitiative.com/Pwn2OwnIreland2025Rules.html), the Pixel 9 and Apple iPhone 16 are priced the same, while the Samsung S25 is priced at only one-third of their cost. It's likely suggests that an all-in isolation-based EL2/hypervisor solution alone may be inadequate for defending against modern threats.

## The era of Code, Trade, F***
As a security researcher, after dedicating months or even years to developing a state-of-the-art zero-day exploit, you'll face a crucial decision: should you sell it to a bug bounty program or a zero-day broker?

| Option                | Pros                                               | Cons                                                |
|-----------------------|----------------------------------------------------|-----------------------------------------------------|
| **Bug Bounty Program**| - **Legitimacy**: Builds reputation as a responsible researcher. <br> - **Higher Value**: Companies may pay well for high-impact finds. <br> - **Support**: Often provides resources and support during the reporting process. <br> - **Ethical Impact**: Contributes to overall security improvements. | - **Limited Payment**: Rewards may not match the full potential market value. <br> - **Disclosure Process**: May require public disclosure timelines, potentially limiting future sales. <br> - **Competition**: Higher competition among researchers could decrease your individual payout. |
| **Zero-Day Broker**   | - **Higher Prices**: Brokers often pay more than bug bounty programs. <br> - **Anonymity**: Allows selling without associating your name with the exploit. <br> - **Flexible Terms**: Brokers may accept terms that allow multiple sales. | - **Legality and Ethics**: Selling to brokers may be seen as unethical or illegal. <br> - **Trust Issues**: The broker's reputation varies; some may not honor payments. <br> - **Market Saturation**: Exploits may lose value if bought in bulk by brokers for resale. |



## Reference
 * Update About the 0-day Industry, https://medium.com/@maor_s/update-about-the-0-day-industry-8d8bb49e8dbb
 * The boom, the bust and the adjust: The offensive cybersecurity industry — trends and updates, https://medium.com/@maor_s/the-boom-the-bust-and-the-adjust-ea443a120c6
 * https://blog.talosintelligence.com/intellexa-and-cytrox-intel-agency-grade-spyware/
