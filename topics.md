# Intro

## Easy
  + Misconfiguration (tipo accesso a .dotfiles via HTTP) (OSI liv 7)
  + Authentication and Session Management
    + Cookie encryption is useless
  + Brute force (OSI liv 7) *
  + SQL Injection (OSI liv 7)
  + XSS (OSI liv 7)
    + Permanente / temporanea

  + CSRF
  + Third party vulns
    + Using CVEs

  ## Case History
    + Twitter XSS
    + HTTPOXY (e qualunque altra specifica del protocollo HTTP) (OSI liv 7)

## Medium
  + Password Timing Attack *
  + DOS & DDOS (OSI liv 4/3)
  + RCE (OSI liv 7/1)
  + MITM (OSI liv 3)
  + ARP Spoofing (OSI liv 3)

## Hard
  + Heap & Stack overflow / underflow *
    - Privilege escalation
    - Remote root
  + Process tracing

  ## Case History
    + Hearthbleed (OSI liv 1)


`*` = da approfondire

**Possibili Iter di attacco combinato:**
  DDOS di un server SQL per manifestare misconfiguration che espone dati sensibili
  Brute force di un utente non privilegiato, per arrivare alla privilege escalation
