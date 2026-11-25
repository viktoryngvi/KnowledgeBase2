# KnowledgeBase2
CySec knowledgebase verkefni 1

## 3.1 Collaborative Lecture Notes

## Lecture 1:
Attack Surface: er heildin af mögulegum veikleikum sem er hægt að gera árás á kerfið, hvort það sé Digital, Physical eða mannlegir veikleikar.
CIA skipti markmiðum tölvuöryggis í 3 megin markmið sem voru Confidentiality, Integrity og Availability.
- Confidentiality: Preventing unauthorized disclosure.
- Integrity: Preventing unauthorized modification or forgery.
- Availability: Keeping systems and data usable when needed.

Það eru líka margar leiðir til að takmarka Attack surface sem er eiginlega bara að fara í gegnum þesar reglur.

Cyber Defence Snýst um að Koma í veg fyrir árásir með því að greina hana, bregðast við og að takmarka skaðann (Attack surface reduction). Maður getur gert það með því að sjá fyrir árásinar og finna veikleika í kerfinu áður en utanaðkomadi aðillar finna þá.

Design Principles: mikilvæg design principles eru til dæmis Least privilege: þar sem notandinn fær aðeins þær heimildir sem hann þarf, 

Fail-safe defaults: banna sjálfgefið nema annað er tekið fram og svo defence in depth: sem er að betrumbæta vörnina sína yfir heildina t.d. firewall og Lykilorð.

Það eru nokkrar tegundir af Malware Mechanisms:
- Worm: forrit sem dreifir sér á milli tölva.
- Trojan: forrit sem fylgir með venjulegum forritum.
- Ransomware: notar dulkóðun til að kúa pening frá eigendum.
- Persistance: Forrit sem haldast í vélinni þrátt fyrir endurræsingu á vélinni
- Command and control: Forrit sem leyfir utanaðkomandi stýringu á vélinni með fjarstjórnun.

##### Categories of computer security threats:
- Unauthorised access
- Unauthorised modification
- Unauthorised disclosure
- Denial of Authorized Access
- Forgery
- Repudiation - where the integrity of an asset can be
- disputed
- Spoofing - masquerading as a legitimate entity

###### CVE Common Vulnerabilities and Exposures:
- CVE(Common Vulnerabilities and Exposures) Skrá yfir opinber þekkt vulnerability
- CVSS(Common Vulnerability Scoring System) alvarleikamat á bilinu 0-10

 ## Gæti gert eitthvað um þekktar árásir


## Lecture 2:

### Virtualization (Sýndarvæðing):
Virtualization snýst um að nota hugbúnað til að skipta Vélinni upp í nokkrar sýndarvélar, operating systems, processes eða containers.

Maður ætti að virtualisa af nokkrum ástæðum:
1. Isolation: takmarkar áhrif crashes og árása
2. Sandboxing: prófa óþekktann hugbúnað í einangruðu umhverfi.
3. Multi tenancy: ólýkir notendur geta notað vélina án þess að hafa aðgang að kerfum hvor annara.
4. kostar minna og nýtir vélbúnaðinn betur

### Terminology:
- Host machine: Vélin sem er að keyra Virtualisationið
- Host OS: kerfið sett upp á Host machine
- Guest Machine: Vélin sem er sett upp á host
- Guest Host: Stýrikerfið sem er inni í vélinni
- Hypervisor(VMM): Hugbúnaður sem býr til, keyrir og stjórnar VM
- Orchestration: Sjálfvirk uppsetning, skölun og nettenging containera

Það eru til 2 tegundir af Hypervisor:
1. Bare-metal Hypervisor: Keyrir beint á vélbúnaði
2. Hosted Hypervisor: keyrir application á Host OS

### Virtualization methods:
- Full Virtualization: Guest OS keyrir beint á sýndarvélbúnaði
- Hardware assisted Virtualization: Nýtir Cpu-eiginleika til að hraða virtualization.
- Paravirtualization: Guest OS notar sérstaka drivers eða Hypercalls til að vinna með hypervisor... það getur samt bætt við afköst og dregið r compatability
- os-level virtualization: Containers deila sama kernel en hafa einangrað user space
- Emulation: Hermir eftir Vélbúnaði og instruction set. Getur jafnvel hermt eftir öðru CPU arcitecture.

|
|
|
|
|
|
|


### Lecture 3:

## 3.2 Terminology Glossary

## 3.3 Online Resources Library

## 3.4 Tools and Command Compendium
