{% include navigation.html %}
## 5.1: Beneficial and Harmful Effects
* Accelerometers: automobile industry drove price down
   * Used for airbag deployment and lateral movement detection
* Benefits of multirotor- deliveries, harmful- flying in unregulated zones is illegal and dangerous, privacy
* Benefits of Wii- active playing video games, harmful- broken TVs/ injuries
* 3D printers: open source software for computer and printer
   * Organs, prosthetics, houses, shoes, jewelry
* Internet originally for scientists but now used by many people all the time
* Dopamine feedback loops
* Sleep deprivation, depression, anxiety, impulsivity
* **Microtransactions**: “free” games/apps
   * Cosmetics paywall to functionality, pay to win
   * Gold, v-bucks, chips
   * Loot boxes- banned in some countries; gambling

## 5.2: Digital Divide
* Digital divide: differing access to computing devices/ internet based on socioeconomic, geographic, demographic (age, religion)
* Some countries computers not common in rural areas, small # of websites, internet used to protect and advocate the government

## 5.3: Computing Bias
* Explicit Data: data that you voluntarily give to companies
   * Thumbs
   * Name, address…
* Implicit Data: 
   * When you watch
   * What you binge(d)
   * Style of show frequently selected
* Computing innovations can reflect existing tendencies
* Biases can be embedded at all levels of software development

## 5.4: Crowdsourcing
* Citizen Science
   * Describes scientific research that the common population helps to conduct. Ordinary citizens help contribute data to research projects using computing      devices. 
   * Citizen science gives a wide range of people the ability to contribute to scientific studies and, in turn, provides more diverse data for scientists        to work with.
* Crowdsourcing 
   * Practice of getting a large amount of input or information from people on the Internet.
   * Citizen science is an example of crowdsourcing, but crowdsourcing can also take other forms.
   * Crowdsourcing can also take the form of financial support in a process known as crowdfunding like GoFundMe


## 5.5: Legal and Ethical Concerns
* Concerns raised about intellectual property, where content creators have to contend with challenges to their rights to own, sell and use their works.
* Copyright is the right that the creator of a work has to determine who gets to use it. However, the digital age has created new challenges to copyright and demands new ways to protect it as well.
   * Creative Commons is a public copyright license that a creator uses when they want to give others the right to use their work.
   * Open-sourcing allows for work to be freely shared, distributed, and modified. Open source is usually mentioned in the context of software.
   * Open access refers to research available to the general public that's free of many restrictions. For example, some academic journals are open access or have open access sections.
* Illegal streaming software, on the other hand, can violate copyright law and deprive creators of much-needed revenue.
* Biased algorithms, tracking, digital divide, misinformation, political polarization through social media, free speech issues 

### Github Pages Actions
1. Licenses: Creative Commons Zero v1.0 Universal, Open Source MIT License, Open Source GPL License
2. We chose the Open Source GPL License since it allows for work to be freely shared and modified and we want ore people to have access to our website since we are creating it for a business. 
 
## 5.6: Safe Computing
* Safe computing means protecting your personally identifiable information, or (PII), information that can be used to identify you
   * Age, Race, Phone Numbers, Medical information and biometric data (fingerprints, eye scans), Financial Information, Social Security number
   * Various other pieces of personal data, such as your location, cookies, and browsing history, can also be used to find your personal information.
* Search engines can track your search history and use it to suggest websites and search phrases. They can also show you ads based on your search history, part of a process known as targeted marketing.
* Devices, websites, and networks can collect information about a user's location, such as recording the IP address of the devices they use.
* The collection of personal information can be used to enhance your experience online. It can help you connect with friends on social media or find products best suited to you faster.
* Without strong protections, this collection of information might be exploited for ill.
* Your computer might become infected with a virus or a worm. A virus is a malicious program. 
   * Viruses are attached to infected files and must be activated by the user while worms can operate independently.
* Other key issues: 
   * Malware, short for malicious software, is intended to damage or take partial control over a computing system. It also includes ransomware and adware.
   * Phishing works by tricking users into providing their personal information by posing as a trustworthy group.
   * Scammers can also take advantage of keylogging technology, recording your keystrokes to gain access to sensitive information like passwords.
   * The information you send over public networks, like the Wifi network at a coffee store, has the potential to be intercepted by those with harmful ends through a rogue access point, which gives unauthorized access to a secure network.
* A key way to practice safe computing is to be wary. 
* Authentication measures keep people from gaining unauthorized access to your accounts.
   * A strong password is a password that's easy for you to remember but difficult for someone else to guess,
   * Multifactor authentication is provided by the website you're using, although you can generally choose to opt in or out of it. Multifactor authentication is a way to control who gets access to your accounts by requiring multiple (at least two) methods of verification.
      * Knowledge: this is something you know, like a password or PIN number. This can also include verification questions. (What's your favorite food? Where were you born?)
      * Possession: this is something that you have or own, such as a USB drive or an access badge. This can also include one-time passwords sent to a different device like your cell-phone.
      * Inheritance: this is something that you own intrinsically, like your fingerprints or voice.
* Encryption, another way of protecting people's data, is the process of encoding data to prevent unwanted access. (Decryption is the process of decoding data.) 
   * Both of these encryption methods use a key, or a secret piece of information, to keep their messages secret. Only the person the message is intended for should know the key.
* Symmetric key encryption, which uses one key for both encrypting and decrypting code.
* Public key encryption, which uses a public key to encrypt but a private key to decrypt the message.
   * The public key encryption system relies on digital certificates. These are issued by Certificate Authorities (CAs) to trusted sites. They allow other computers to verify that a website is who they say they are. 
* To protect: regular software updates, computer virus and malware scanning software, firewalls, etc

### Github Pages Actions
1. I have seen Personal Identifiable Information (PII) in the CSP nighthawkcodingsociety website which links to twitter, github, and other information
2. I am very safe on the internet and never give my PII to strangers, but I know that if you try and look you can find some of my personal information. But other than my name, birthday, and residence, I don’t think the internet has access to my PII.
3. Passwords
      * Good passwords are long with a mix of upper and lower case letters, numbers, and symbols.
      * Bad Passwords have ties to your personal information (family names, dog name, birthday) and dictionary words.
      * 2 Factor Authentication is extremely prevalent in our soctiety today. Emais, texts, and software-based authenticators like Google Authenticator are great ways to assist with authentication
4. Unlike symmetric encryption, which uses the same secret key to encrypt and decrypt sensitive information, asymmetric encryption, also known as public-key cryptography or public-key encryption, uses mathematically linked public- and private-key pairs to encrypt and decrypt senders’ and recipients’ sensitive data.
5. When deploying we initally used HTTP which did not have encryption. But then we used HTTPS which is HTTP with encryption. The difference between the two protocols is that HTTPS uses TLS (SSL) to encrypt normal HTTP requests and responses.
6. Deceptive phishing is the most common type of phishing scam. In this ploy, fraudsters impersonate a legitimate company to steal people’s personal data or login credentials. Those emails use threats and a sense of urgency to scare users into doing what the attackers want.
