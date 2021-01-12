# awesome-blueteam
A list of resources to build an information security team.

## Philosophy and Process

**[The why, what, and how of threat research](https://redcanary.com/blog/threat-research-questions/)** - Matt Graeber, RedCanary

An excellent overview of how to approach creating a new detection from the initial idea, research, and development.

**[Introducing the Funnel of Fidelity](https://posts.specterops.io/introducing-the-funnel-of-fidelity-b1bb59b04036)** - Jared Atkinson, SpecterOps

A model that breaks down the scope of different stages of detection, which helps focus on the tools and technologies needed at each phase.

## Microsoft Windows

**[What Happens When You Type Your Password Into Windows?](https://syfuhs.net/what-happens-when-you-type-your-password-into-windows)** - Steve Syfuhs, Microsoft

A definitive breakdown of the authentication process on Windows.

**[How Does Windows Defender Credential Guard Work?](https://syfuhs.net/how-windows-defender-credential-guard-works)** - Steve Syfuhs, Microsoft

A review of how Credential Guard protects passwords on Windows from credential theft, in some scenarios.

**[Reading Your Way Around UAC, Part 1](https://www.tiraniddo.dev/2017/05/reading-your-way-around-uac-part-1.html)**, **[Part 2](https://www.tiraniddo.dev/2017/05/reading-your-way-around-uac-part-2.html)**, **[Part 3](https://www.tiraniddo.dev/2017/05/reading-your-way-around-uac-part-3.html)** - James Forshaw, Google Project Zero

An extensive exploration of how User Account Control works on Windows, and ways to bypass it. It took me several rereadings of this series to fully grok it.

**[Introduction to Windows tokens for security practitioners](https://www.elastic.co/blog/introduction-to-windows-tokens-for-security-practitioners)** - Will Burgess, Elastic

An introduction to the "base unit" of Windows access control, the access token, and how it ties into logon sessions. 

**[Restricting SMB-based lateral movement in a Windows environment](https://medium.com/palantir/restricting-smb-based-lateral-movement-in-a-windows-environment-ed033b888721)** - Palantir

SMB-based lateral movement is a frequently used technique by adversary groups, and underpins PSExec, CrackMapExec, and many other tools. This blog post covers many built-in Windows security controls that can be enabled to restrict SMB movement within an environment.

**[Detecting Windows Endpoint Compromise with SACLs](https://medium.com/@cryps1s/detecting-windows-endpoint-compromise-with-sacls-cd748e10950)** - Dane Stuckey, Palantir

A case study in using System Access Control Lists (SACLs) as part of Windows advanced auditing to detect common indicators of successful code execution, lateral movement, or other compromises.

## Technical Background

**[The Illustrated TLS Connection](https://tls.ulfheim.net/)** - Michael Driscoll

A detailed breakdown of a TLS Connection, at every stage, with annotated examples showing exactly how it looks "on-the-wire". Fantastic for anyone looking to write a parser or fully understand what is sent for every TLS connection, and at what stage.


**[Portable Executable File Format](https://blog.kowalczyk.info/articles/pefileformat.html)** - Krzysztof Kowalczyk

A useful reference for the PE Format, the most common executable format on Microsoft Windows, and how that information is stored at the file and structural level. Incredibly thorough, with datatypes and structures to build off if you're working with the format.

**[DigitalOcean Tutorials](https://www.digitalocean.com/community/tutorials)** - DigitalOcean

An excellent collection of short, practical articles about systems administration and the complex stack of technologies you'll often run into, often with detailed practical manuals to work with them. Example: **[How To Use Journalctl to View and Manipulate Systemd Logs](https://www.digitalocean.com/community/tutorials/how-to-use-journalctl-to-view-and-manipulate-systemd-logs)**.



