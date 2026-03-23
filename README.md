# Red Team Ferramentas

Colecao de ferramentas open source e comerciais para operacoes de red team. Este repositorio serve como referencia durante engajamentos ofensivos.

---

## Conteudo

- [Reconhecimento](#reconhecimento)
- [Armamentizacao](#armamentizacao)
- [Entrega](#entrega)
- [Comando e Controle](#comando-e-controle)
- [Movimento Lateral](#movimento-lateral)
- [Estabelecer Acesso](#estabelecer-acesso)
- [Escalada de Privilegios](#escalada-de-privilegios)
- [Exfiltracao de Dados](#exfiltracao-de-dados)
- [Misc](#misc)
- [Referencias](#referencias)

---

## Reconhecimento

### Coleta Ativa

| Ferramenta | Descricao | Link |
|---|---|---|
| EyeWitness | Tira screenshots de sites, coleta headers e identifica credenciais padrao | https://github.com/ChrisTruncer/EyeWitness |
| AWSBucketDump | Enumera buckets S3 da AWS em busca de arquivos expostos | https://github.com/jordanpotti/AWSBucketDump |
| AQUATONE | Conjunto de ferramentas para reconhecimento em dominios | https://github.com/michenriksen/aquatone |
| spoofcheck | Verifica se um dominio pode ser falsificado via SPF/DMARC fraco | https://github.com/BishopFox/spoofcheck |
| Nmap | Scanner de hosts e servicos em redes | https://github.com/nmap/nmap |
| dnsrecon | Script de enumeracao DNS | https://github.com/darkoperator/dnsrecon |
| dirsearch | Brute force de diretorios e arquivos em sites | https://github.com/maurosoria/dirsearch |
| Sn1per | Scanner automatizado de recon para pentest | https://github.com/1N3/Sn1per |

### Coleta Passiva

| Ferramenta | Descricao | Link |
|---|---|---|
| Social Mapper | Mapeamento OSINT em redes sociais em larga escala | https://github.com/SpiderLabs/social_mapper |
| skiptracer | Framework OSINT para compilar informacoes passivas de alvos | https://github.com/xillwillx/skiptracer |
| FOCA | Encontra metadados e informacoes ocultas em documentos publicos | https://github.com/ElevenPaths/FOCA |
| theHarvester | Coleta subdominios, emails, hosts e nomes de funcionarios | https://github.com/laramies/theHarvester |
| Metagoofil | Extrai metadados de documentos publicos (pdf, doc, xls, ppt) | https://github.com/laramies/metagoofil |
| truffleHog | Busca secrets em repositorios git com historico de commits | https://github.com/dxa4481/truffleHog |
| pwnedOrNot | Verifica se emails foram comprometidos em vazamentos | https://github.com/thewhiteh4t/pwnedOrNot |
| GitHarvester | Coleta informacoes do GitHub via Google dork | https://github.com/metac0rtex/GitHarvester |
| LinkedInt | Ferramenta de recon no LinkedIn | https://github.com/vysecurity/LinkedInt |
| findomain | Enumeracao rapida de dominios via Certificate Transparency | https://github.com/Edu4rdSHL/findomain |

### Frameworks

| Ferramenta | Descricao | Link |
|---|---|---|
| Maltego | Plataforma de inteligencia e mapeamento de ameacas | https://www.paterva.com |
| SpiderFoot | Framework open source de footprinting e inteligencia | https://github.com/smicallef/spiderfoot |
| Recon-ng | Framework completo de reconhecimento web em Python | https://github.com/lanmaster53/recon-ng |

---

## Armamentizacao

| Ferramenta | Descricao | Link |
|---|---|---|
| Veil | Gera payloads Metasploit que bypassam antivirus comuns | https://github.com/Veil-Framework/Veil |
| SharpShooter | Framework de criacao de payloads para execucao de C# | https://github.com/mdsecactivebreach/SharpShooter |
| Invoke-Obfuscation | Ofuscador de PowerShell | https://github.com/danielbohannon/Invoke-Obfuscation |
| Unicorn | Injeta shellcode na memoria via downgrade attack do PowerShell | https://github.com/trustedsec/unicorn |
| Shellter | Ferramenta dinamica de injecao de shellcode em PE | https://www.shellterproject.com |
| Donut | Gera shellcode a partir de assemblies .NET | https://github.com/TheWover/donut |
| macro_pack | Automatiza ofuscacao e geracao de documentos Office maliciosos | https://github.com/sevagas/macro_pack |
| EvilClippy | Cria documentos Office maliciosos com macros ocultas | https://github.com/outflanknl/EvilClippy |
| PSAmsi | Ferramenta para auditoria e bypass de assinaturas AMSI | https://github.com/cobbr/PSAmsi |

---

## Entrega

### Phishing

| Ferramenta | Descricao | Link |
|---|---|---|
| GoPhish | Framework open source de phishing para empresas e pentesters | https://github.com/gophish/gophish |
| King Phisher | Simula ataques de phishing reais para testes de conscientizacao | https://github.com/securestate/king-phisher |
| Evilginx2 | Framework MitM para captura de credenciais e cookies de sessao | https://github.com/kgretzky/evilginx2 |
| Modlishka | Proxy reverso flexivel para campanhas de phishing etico | https://github.com/drk1wi/Modlishka |
| CredSniper | Framework de phishing com suporte a captura de tokens 2FA | https://github.com/ustayready/CredSniper |
| ReelPhish | Ferramenta de phishing 2FA em tempo real | https://github.com/fireeye/ReelPhish |

---

## Comando e Controle

| Ferramenta | Descricao | Link |
|---|---|---|
| Cobalt Strike | Software profissional para simulacoes de adversarios e red team | https://cobaltstrike.com |
| Metasploit Framework | Framework classico de pentest e exploracao de vulnerabilidades | https://github.com/rapid7/metasploit-framework |
| Empire | Framework de pos-exploracao com agentes PowerShell e Python | https://github.com/EmpireProject/Empire |
| Sliver | Framework de implant cross-platform com C2 via mTLS, HTTPS e DNS | https://github.com/BishopFox/sliver |
| Covenant | Framework C2 em .NET com interface colaborativa para red teams | https://github.com/cobbr/Covenant |
| Merlin | Servidor e agente C2 HTTP/2 cross-platform em Go | https://github.com/Ne0nd0g/merlin |
| Pupy | Ferramenta de administracao remota e pos-exploracao em Python | https://github.com/n1nj4sec/pupy |
| PoshC2 | Framework C2 proxy-aware escrito em PowerShell | https://github.com/nettitude/PoshC2_Python |
| DNScat2 | Cria canal C2 criptografado sobre protocolo DNS | https://github.com/iagox86/dnscat2 |

---

## Movimento Lateral

| Ferramenta | Descricao | Link |
|---|---|---|
| CrackMapExec | Canivete suico para pentesting em redes Windows | https://github.com/byt3bl33d3r/CrackMapExec |
| BloodHound | Revela relacionamentos ocultos no Active Directory via graph theory | https://github.com/BloodHoundAD/BloodHound |
| Mimikatz | Extrai credenciais e hashes do processo lsass do Windows | https://github.com/gentilkiwi/mimikatz |
| Impacket | Colecao de classes Python para trabalhar com protocolos de rede | https://github.com/CoreSecurity/impacket |
| Responder | Envenenador LLMNR/NBT-NS/MDNS com servidor de autenticacao falso | https://github.com/SpiderLabs/Responder |
| PowerSploit | Colecao de modulos PowerShell para todas as fases do pentest | https://github.com/PowerShellMafia/PowerSploit |
| Nishang | Framework de scripts PowerShell para seguranca ofensiva | https://github.com/samratashok/nishang |
| LaZagne | Recupera senhas armazenadas localmente em diversas aplicacoes | https://github.com/AlessandroZ/LaZagne |
| MailSniper | Busca termos especificos em emails de ambientes Microsoft Exchange | https://github.com/dafthack/MailSniper |
| SessionGopher | Extrai sessoes salvas de WinSCP, PuTTY, FileZilla e outros via WMI | https://github.com/fireeye/SessionGopher |
| LOLBAS | Documenta binarios e scripts do Windows usaveis para evasao | https://github.com/api0cradle/LOLBAS |

---

## Estabelecer Acesso

| Ferramenta | Descricao | Link |
|---|---|---|
| Tunna | Tunnela comunicacao TCP sobre HTTP para bypass de firewall | https://github.com/SECFORCE/Tunna |
| reGeorg | Cria proxies SOCKS atraves de webservers comprometidos | https://github.com/sensepost/reGeorg |
| PowerLurk | Constroi assinaturas de eventos WMI maliciosos com PowerShell | https://github.com/Sw4mpf0x/PowerLurk |

---

## Escalada de Privilegios

### Active Directory

| Ferramenta | Descricao | Link |
|---|---|---|
| BloodHound | Mapeia caminhos de escalada no AD via graph theory | https://github.com/BloodHoundAD/BloodHound |
| PowerView | Ferramenta PowerShell para situational awareness em dominios Windows | https://github.com/PowerShellMafia/PowerSploit |
| Rubeus | Toolset C# para interacao e abuso do Kerberos | https://github.com/GhostPack/Rubeus |
| ADRecon | Extrai artefatos detalhados do AD em relatorio Excel formatado | https://github.com/sense-of-security/ADRecon |
| LAPSToolkit | Auditoria e ataque em ambientes LAPS | https://github.com/leoloobeek/LAPSToolkit |
| Grouper | Encontra configuracoes vulneraveis em Group Policy do AD | https://github.com/l0ss/Grouper |

### Escalada Local

| Ferramenta | Descricao | Link |
|---|---|---|
| UACMe | Colecao de metodos para bypass do UAC do Windows | https://github.com/hfiref0x/UACME |
| PowerUp | Identifica vetores comuns de escalada local por misconfiguracao | https://github.com/PowerShellMafia/PowerSploit |
| windows-kernel-exploits | Colecao de exploits de kernel do Windows | https://github.com/SecWiki/windows-kernel-exploits |
| Sherlock | Script PowerShell para encontrar patches ausentes de privilege escalation | https://github.com/rasta-mouse/Sherlock |

---

## Exfiltracao de Dados

| Ferramenta | Descricao | Link |
|---|---|---|
| DNSExfiltrator | Transfere arquivos via canal encoberto em requisicoes DNS | https://github.com/Arno0x/DNSExfiltrator |
| PyExfil | Pacote Python para exfiltracao de dados por multiplos canais | https://github.com/ytisf/PyExfil |
| CloakifyFactory | Exfiltracao de dados disfarçada para evasao de DLP | https://github.com/TryCatchHCF/Cloakify |

---

## Misc

### Emulacao de Adversarios

| Ferramenta | Descricao | Link |
|---|---|---|
| MITRE CALDERA | Sistema automatizado de emulacao de adversarios pos-comprometimento | https://github.com/mitre/caldera |
| Atomic Red Team | Testes de deteccao mapeados ao framework MITRE ATT&CK | https://github.com/redcanaryco/atomic-red-team |
| APTSimulator | Simula comprometimento de sistema via batch script | https://github.com/NextronSystems/APTSimulator |

### Redes Wireless

| Ferramenta | Descricao | Link |
|---|---|---|
| Wifiphisher | Realiza ataques de associacao automatica Wi-Fi | https://github.com/wifiphisher/wifiphisher |

### Frameworks C# Ofensivos

| Ferramenta | Descricao | Link |
|---|---|---|
| SharpSploit | Biblioteca .NET de pos-exploracao escrita em C# | https://github.com/cobbr/SharpSploit |
| GhostPack | Colecao de implementacoes C# de ferramentas ofensivas | https://github.com/GhostPack |
| SharpView | Implementacao C# do PowerView | https://github.com/tevora-threat/SharpView |

---

## Referencias

| Recurso | Descricao | Link |
|---|---|---|
| MITRE ATT&CK | Base de conhecimento de comportamentos de adversarios ciberneticos | https://attack.mitre.org |
| Red Team Infrastructure Wiki | Recursos para hardening de infraestrutura de red team | https://github.com/bluscreenofjeff/Red-Team-Infrastructure-Wiki |
| Awesome Red Teaming | Lista curada de recursos de red team | https://github.com/yeyintminthuhtut/Awesome-Red-Teaming |
| APT Notes | Colecao de papers e blogs sobre campanhas APT | https://github.com/aptnotes/data |
| HarmJ0y CheatSheets | Cheat sheets para Cobalt Strike, PowerView, Empire e outros | https://github.com/HarmJ0y/CheatSheets |

---

Autor: russo-sec | nyx11
