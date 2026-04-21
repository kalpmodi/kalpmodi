```
┌──(kalpmodi㉿kali)-[~]
└─$ whoami
kalpmodi

┌──(kalpmodi㉿kali)-[~]
└─$ id
uid=1337(kalpmodi) gid=1337(bugbounty) groups=1337(bugbounty),31337(0day),999(cve-researcher)

┌──(kalpmodi㉿kali)-[~]
└─$ uname -a
Linux kali 6.6.0-kali-amd64 #1 SMP PREEMPT Kali 6.6.9-1kali1 x86_64 GNU/Linux

┌──(kalpmodi㉿kali)-[~]
└─$ cat /etc/kalpmodi/profile
-------------------------------------------------------------
  name     : Kalp Modi
  role     : Offensive Security Researcher · Bug Bounty Hunter
  location : India
  focus    : Web App · Cloud Misconfigs · OAuth/JWT · Race Conditions
  cve      : Strapi SSRF Bypass + MIME Fail-Open [ filed 2026 ]
  platforms: HackerOne · Bugcrowd · Private Programs
-------------------------------------------------------------

┌──(kalpmodi㉿kali)-[~]
└─$ ls -la ~/projects/
drwxr-xr-x  kalpmodi  akira/              [ AI pentest co-pilot · 12 skills · MIT ]
drwxr-xr-x  kalpmodi  EvilTwin-ESP32/     [ hardware Wi-Fi spoofing demo · C++ ]
drwxr-xr-x  kalpmodi  PostmapDB/          [ Shodan for Postman · in development ]

┌──(kalpmodi㉿kali)-[~]
└─$ cat ~/projects/akira/README | head -5
  phase-chained AI pentest co-pilot
  /plan-engagement → /recon → /secrets → /exploit → /triage → /report
  evidence-gated · no hallucinations · runs in Claude Code · Gemini CLI · Cursor
  github.com/kalpmodi/akira

┌──(kalpmodi㉿kali)-[~]
└─$ cat ~/skills.txt
  [ web ]    XSS · SQLi · SSRF · SSTI · XXE · NoSQLi · Deserialization
  [ auth ]   JWT confusion · OAuth redirect · PKCE downgrade · CSRF
  [ infra ]  AWS IAM privesc · S3 enum · GCP · Azure RBAC · K8s API
  [ ad ]     BloodHound · Kerberoasting · DCSync · Golden Ticket · ADCS ESC1-8
  [ logic ]  Race conditions · HTTP/2 single-packet · double-spend · OTP bypass
  [ lang ]   Python · TypeScript · C++ · Shell · Bash

┌──(kalpmodi㉿kali)-[~]
└─$ git log --oneline ~/projects/akira | head -5
1017c55  redesign: minimal profile README
787cb85  chore: remove weekly findings reminder workflow
6d56f1e  docs: clarify vulnerability reporting process
5cd3cdf  docs: add CI badge, fix findings reference
ab44e67  chore: exclude non-essential files from archive downloads

┌──(kalpmodi㉿kali)-[~]
└─$ curl -s https://api.github.com/users/kalpmodi | jq '{stars: .public_repos, followers: .followers}'
{
  "followers": 6,
  "public_repos": 16
}

┌──(kalpmodi㉿kali)-[~]
└─$ cat ~/links.txt
  linkedin  → https://linkedin.com/in/kalpmodi17704
  github    → https://github.com/kalpmodi
  coffee    → https://buymeacoffee.com/kalpmodi
  sponsor   → https://github.com/sponsors/kalpmodi

┌──(kalpmodi㉿kali)-[~]
└─$ █
```