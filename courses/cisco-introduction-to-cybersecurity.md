# Cisco Introduction to Cybersecurity

## Course

- Provider: Cisco Networking Academy / Skills for All
- Level: Beginner
- Status: In progress
- Start date: 2026-08-25
- Completion date: TBD
- Official course link: [(https://www.netacad.com/dashboard#)]

## Why I am taking it

I am using this course to establish a broad foundation before studying
network security, security operations, and application security.

## Learning objectives

- Explain the main goals of cybersecurity.
- Identify common threats and attacks.
- Describe basic organizational security controls.
- Understand why cybersecurity matters to businesses.
- Identify cybersecurity career areas.

## Module notes

### Module 1: Intro to Cybersecurity

 
- Main concepts:
                Cybersecurity: ongoing effort to protect individuals, organistations and govts from digital attacks by protecting networks and data.

                Personal Data: can be used for individuals identification. Exists both online and offline. Offline identity data, or the real-life persona, includes full name, age and address. Online identity is your online presentation. Usernames, alias for online accounts, and social identity portrayed on online communities and websites.

                No social-media, does not mean no online identity. If you use the web, you have an online identity.

                Usernames - Important points in creating one:
                                               - No parts of address or phone number.
                                               - No email username
                                               - Don't repeat username and password combination
                                               - repeated super-odd username makes you easier to track
                                               - No clues to passwords in usernames.
                                               - Choose one that is appropriate for the type of                                                         account.

                Identity Theft - criminals focus on longer term benefit.

                ISP tracks your internet habits and can even sell this data to advertisers in some countries. Some countries may even oblige them to share this data with the government surveillance agencies.
                In fact, we are constantly being "monitored", search engines and social media platforms will sell your data for advertisers and websites will use cookies to track you and sell your data also to advertisers.

                1.2 Organizational Data
                1.2.1 Data types
                      > Transactional data. Related to organizations' operations.
                      > Intellectual Property. Patents, trademarks, new product plans. Often consider trade secret.
                      > Financial data. Income statements, cash flows... that provide insight of the companies' health.

                      > IoT and Big Data. Every object connected to the internet with the ability to collect and share data.

                      
                1.2.2 The Cube
                      John McCumber creation to help organizations establish and evaluate information security initiatives.
                      It has 3 dimensions:
                                    1. foundation principles for protecting information systems.
                                    2. Protection of information in each of its possible states.
                                    3. Security measures to protect data.





               3.1 Protecting your device and Network.

   Protecting your computing devices. Basic steps for a new device.

      - turn on firewall
        either a software or a hardware on a router
      - install antivirus and antispyware
      - manage o.s. and browser
        keep them updated and with the latest patchs.
      - set up password protection
        regardless of password encrypt your sensitive data.


   IoT devices present a greater risk than other computing devices. They tend to keep their original software with all the vulnerabilities "attached". Most of them require internet access and most often they are connected to your local network. By connecting these devices to your local network hackers can break into your network through your IoT device. Best practice is to isolate IoT devices in a different network.
    
   Shodan.io - web-based IoT device scanner that helps identify vulnerable IoT devices.

            3.1.3 Wireless Network Security at Home

   Although a wireless router can be configured not to broadcast the SSID, this is not adequate security for wireless network.
   These detais should be changed. Additionally, one should encrypt wireless communication by enagbling wireless security and the WPA2 encryption feature on their router. Even doing so, a wireless network can still be vulnerable.

   Hackers will try to break the encryption between router and wireless device using a Key Reinstallation Attack (KRACK). When successful they get access to network data.
  Mitigation actions:
      - update all wireless devices security softwares as soon as new patchs are available.
      - use wired connection for devices with wired network interface card (NIC)
      - use VPN when accessing a wireless network.

          3.1.4 Public wi-fi risks
          Never access or send any personal information using public WI-FI.
          Verify that your device is not configured with file and media sharing and that it requires user authentication with encryption.
          Use encrypted VPN service to prevent information interception ('eavesdropping') over public wireless network. Even if hackers intercept a data transmission in an encrypted VPN tunnel, they will not be able to decipher it.
          
       Recommendations from the FCC

  **Public Wi-Fi Access**

Many Wi-Fi users choose to use public networks instead of a device's data plan for accessing the internet. But the convenience of public Wi-Fi can be risky. Hackers can access your connection and compromise sensitive information stored on your devices and in your online accounts. Here are some steps you can take to minimize the risk:

    Watch out for imposter public Wi-Fi hotspots. If more than one hotspot seems to belong to an establishment that you're in, check with the staff to avoid connecting to an imposter hotspot.
    Make sure all websites you exchange information with have "https" at the beginning of the web address. The "s" in "https" stands for "secure," so your transmitted data will be encrypted and much less likely to be hacked.
    Install an app add-on that forces your web browsers to use encryption when connecting to websites.
    Adjust your cellphone settings so it does not automatically connect to nearby Wi-Fi networks that are not on your short list of trusted networks.
    If you use public Wi-Fi hotspots on a regular basis, consider using a virtual private network (VPN), which will encrypt all transmissions between your device and the internet. Many companies offer VPNs to their employees for work purposes, and individuals may subscribe to VPNs on their own.
    When transmitting sensitive information, using your cellphone data plan instead of Wi-Fi may be more secure.

**Bluetooth Security**

Bluetooth connections to your mobile devices can be used to connect to wireless headsets, transfer files, and enable hands-free calling while you drive, for example. Most of the time, a user must allow a Bluetooth connection to occur before data is shared – a process called "pairing" – which provides a measure of data security. But like Wi-Fi connections, Bluetooth can put your personal data at risk. Here are some steps you can take when using Bluetooth:

    Turn Bluetooth off when not in use. Keeping it active enables hackers to discover what other devices you connected to before, spoof one of those devices, and gain access to your device.
    If you use Bluetooth to connect your mobile phone to a rental car, be sure to unpair your phone and clear any personal data from the car before you return it. Take the same steps when selling a car that has Bluetooth.
    Use Bluetooth in "hidden" mode rather than "discoverable" mode. This prevents other unknown devices from finding your Bluetooth connection.

**Home Wireless Network Security**

Home wireless networks enable computers and mobile devices to share one broadband connection to the internet wirelessly all over your home. But home wireless networks have vulnerabilities that hackers can exploit. To help protect your home network from unwanted users, consider the following steps:

    Turn on encryption. Wireless routers often come out of the box with the encryption feature disabled, so be sure it is enabled when you set up your network. 
    Change the network's default network name, also known as its service set identifier or "SSID." When a computer with a wireless connection searches for and displays the wireless networks nearby, it lists each network that publicly broadcasts its SSID. Manufacturers usually give all of their wireless routers a default SSID, which is often the company's name. For additional security, choose a unique and hard-to-guess name as your SSID.
    Change the network's default password. Most wireless routers come with preset passwords for administering a device's settings (this is different from the password used to access the wireless network itself). Hackers may be familiar with the default passwords, so it is important to change the router device's password when you install it. Longer passwords made up of a combination of letters, numbers, and symbols are more secure.
    For added security, activate the Media Access Control or "MAC" address filter in your wireless router. Every device that can connect to a Wi-Fi network has a unique ID called the "physical address" or "MAC" address. Wireless routers can screen the MAC addresses of all devices that connect to them, and you can set your wireless network to accept connections only from MAC addresses that you approve.
    Turn off your wireless router when it will not be in use for an extended period of time.
    Use security apps on your computer and  on mobile devices that access your wireless network.

 3.1.7 Using a Passphrase
      Use good password practices but instead of word create a phrase. 

 Guidelines from NIST. Aim is to place responsability on service providers:

    * Min 8 characters, max 64.
    * Dumb passwords, like "password" or "abc123" shall not be used.
    * No composition rules, such as having to include lower and uppercase letters and numbers.
    * Password should be visible when typing to help accuracy.
    * All printing characters and spaces should be allowed.
    * No password hints.
    * No password expiration period.
    * No knowledge-based authentication, such as answer to secret quetions or verify transaction history.


    3.2 Data Maintenance

    Encryption does not prevent data interception. It can only prevent unauthorized people from viewing the content. Some criminals will encrypt your data and make it unusable until ransom is paid.

    Software programs encrypt data. Encrypting file system (EFS) is a windowns feature for encrypting data. 

    3.2.3 Back up your data.
    Have a backup of all your important data in case your devices (computer, phone..) are lost or stolen. Copy it regularly to a chosen location.
    Additional storage locations.
     * Home Network (locally stored)
     * NAS (network attached storage) - external hard drive, thumb drives, CD, DVD, tapes...
     * Cloud storage service. You have a backup as long as you have an account. Keeps your data safe from device failure or extreme situations such as fire or theft.
















  
- New terminology:
                  ISP (Internet Service Provider)
                  SSID (Service Set Identifier) - preset network identifier
                  NIC (Network interface card)
                  MAC (Media Access Control or "physical address")
                  White hat hacker
                  Grey hacker
                  Black hacker
                          
        
- Practical example:
                    Hackers may not only steal your money but also "steal" your identity and ruin your reputation by taking credits and loans under your name.

                    Cybercriminals were found to be stealing medical insurance to use the benefits for themselves. Leaving you with the insurance bills and a medical record that is not yours.
  
- Questions I still have:

### Module 2: ...

- Main concepts:
- New terminology:
- Practical example:
- Questions I still have:

## Practical exercises

- [ ] Complete lesson exercises
- [ ] Complete knowledge checks
- [ ] Record important terminology
- [ ] Write one personal example
- [ ] Create one small related project

## Final reflection

### What I understand

### What remains unclear

### What I will study next

### Evidence

- Course completion:
- Badge or certificate:
- Related repository files:
