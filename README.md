# SHELLS

A small collection of web shells for use during **authorized** penetration-testing
and red-team engagements. These are intended as payloads for validating
file-upload and remote-code-execution findings on systems you own or have
explicit written permission to test.

## Contents

| File | Platform | Description |
|------|----------|-------------|
| `shell.jsp` | Java / JSP | Minimal JSP web shell for Java application servers (Tomcat, JBoss, etc.) |

## Usage

1. Upload the shell to a writable, web-accessible directory on the target.
2. Browse to it and pass commands via the request parameter it reads.

Deploy only against lab environments or engagements covered by a signed
scope/authorization.

## Disclaimer

This repository is provided for **educational purposes and authorized security
testing only**. Using these tools against systems without the owner's explicit
permission is illegal. The author accepts no liability for misuse.
