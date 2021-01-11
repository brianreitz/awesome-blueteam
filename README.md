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
