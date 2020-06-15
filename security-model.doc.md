# Model of System Attack 
To have a consistent and easy to work with model of a computer system attack, we first divide the attack up between external and internal exploitation cycles. These lifecycles are nested and repeated throughout a hack and give us a unit of measure; This model is useful for a variety of reasons, for example, this model provides us a unit of measure that can be used to understand the scale of an attack severity.

The scale of an attack can help us understand how much time was invested; this may be important in understanding who attacked, and why they attacked. For example, the time and cycles required to obtain their overall objective, may indicate how much knowledge the attacker had prior to their first recon action. 

This also provides us with a model to classify and categorize on-going attacks, map out what an intruder did if they successfully attacked, building a time-line for understanding exactly what was taken, and how it was taken. And with this information, system administrators can fix the problem and prevent future attacks, and investigators can try to determine the reason for the attack, and then from that possibly the identity of the attacker. 

Without a model for attacks, its impossible to react to an attack successfully, and without properly responding to system attack; securing a computer system is impossible. 


## Multiverse OS Security Model 
Security is not a vague concept handed off to a few applications with specialized functionality; software that fundamentally has stopped being used ironically as the internet became more dangerous, and malware became more profitable. 

There are a lot of possible explanation for this that we will not discuss here, but this vacant spot in many operating systems was previously filled by virus like software that overall functioned poorly, and used poorly formulated defense strategies. 

For example, many simply used a fingerprint of a file, creating a "blacklist", a method that security experts agree simply is not a viable strategy to defend a computer system against attacks. First, it requires a database of samples to be maintained, which is still done by security researchers like VirusTotal, but this strategy is thrwarted again, and again; and XSS attacks are just one illustration that attack vectors have seemingly unlimited supply of creativity. 

While many developers continue to use "blacklists" despite the security expert consensus being established long ago, its continued usage, combined with growing IT industry treating programming as a trade rather than a science, has resulted in literal planes falling from the sky, and is one of many reasons the internet is now far more dangerous place for average users than ever before. And there appears to be little action being taken to resolve this, average users, are left with insecure boot systems, while industry drags their feet and is only now beginning to offer almost exclusively its enterprise level clients secure boot processes that are still unimpressive. 

#### The "Whitelist" (Accept List) Approach 
In contrast to still commonplace "blacklists", the "whitelist" method of defense is one of many components in a successful strategy to defend a computer system. But not all "whitelist" methods are created equal, and many existing "whitelisting" approaches appear to have alterior motives sewn into their fabric, benefitting operating system developers "app store" sales, but likely hinder their ability to actually provide real protection due to this same misprioritization of goals defining their defense mechanism. 

The method that currently exists within operating systems is "Trusted" vs "Untrusted" enterprises or developers. And what defines a developer or businesses trustability according to existing operating systems is a developer's ability to pay the operating system "app store" software money, or their ability to generate the "app store" money. And this may be one of many possible explanations for the number of existing and removed applications offered with malware either explicitly or implicitly hidden inside. 

This is paired with reducing binary execution through the principle of permissioned access hardware and software tools managed by the operating system. 

The Multiverse OS defense strategy is built around the following simplification of an attack on a computer system. And attempts to find these patterns using a variety of components; including but not limited too anamoly detection, honey-pot style instrusion alarms, dynamically generated strict Linux configurations, executable registry with fine-grain control of specific actions and flags, and a user signature and checksum verification that both the user and the community participates in. 

Below is a sketch of the currently used model for attacks, which are used for both discovering but also analyizing attacks against system infrastructure. 



## External
#### Recon
#### Map
#### Exploit 

### Complete Objective 

## Internal
#### Recon 
#### Map 
#### Exploit 

### Complete Objective
