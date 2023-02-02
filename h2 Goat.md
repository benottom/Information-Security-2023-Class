# h2 Goat
Starting with the instructor statement to keep it secure, compliant and moral. Make a good point to state - while learning ethical hacking - to NOT attempt any actions on machines you don't possess.
# OWASP: [OWASP 10 2021](https://owasp.org/Top10/)

## A06:[2021 - Vulnerable and Outdated Components](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/)
### Overview
* Vulnerable Components are a known issue that organizations struggle to test and assess risk for
* No Common Vulnerability and Exposures (CVEs) are mapped to the included CWEs, a default exploits/impact weight of 5.0 is used
* Notable CWEs: CWE-1104: Use of Unmaintained Third-Party Components, CWEs from Top 10 2013 and 2017

### You are likely vulnerable:
* If you don't know the versions of all components used (client-side and server-side)
* If software is unsupported, out of date, or vulnerable
* If you don't regularly scan for vulnerabilities and subscribe to security bulletins
* If you don't fix/upgrade platform, frameworks, dependencies in a timely fashion
* If developers don't test the compatibility of updated libraries
* If you don't secure the components' configurations

### How to prevent:
* Have a patch management process in place
* Continuously inventory and monitor versions of components and dependencies
* Obtain components from official sources over secure links
* Monitor for unmaintained or unpatched components
* Have an ongoing plan for monitoring, triaging, and applying updates/config changes

### Example Attack Scenarios:
* Flaws in components can result in serious impact
* Some example exploitable component vulnerabilities are: CVE-2017-5638, Heartbleed vulnerability
* Automated tools can help attackers find unpatched systems

### References:
* OWASP Application Security Verification Standard, OWASP Dependency Check, OWASP Testing Guide, OWASP Virtual Patching Best Practices
* National Vulnerability Database (NVD), Retire.js, Ruby Libraries Security Advisory Database
* MITRE Common Vulnerabilities and Exposures (CVE) search
* List of Mapped CWEs: CWE-937, CWE-1035, CWE-1104


## A05:[2021 - Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)

### Overview:

* 90% of applications tested for misconfiguration with average incidence rate of 4%
* 208k occurrences of Common Weakness Enumeration (CWE) risk category
* Notable CWEs: CWE-16 Configuration, CWE-611 Improper Restriction of XML External Entity Reference

### Description:

* Vulnerability in the application due to:
* Missing security hardening or incorrect config of cloud services
* Unnecessary features enabled or installed
* Default accounts and passwords unchanged
* Error handling reveals sensitive info
* Outdated or vulnerable software
* Insecure settings in application servers, frameworks, libraries, databases
* Server not sending security headers or directives

### Prevention:

* Implement secure installation process
* Repeatable hardening process
* Minimal platform without unnecessary features
* Review and update security configurations
* Segmented application architecture
* Send security directives to clients
* Automated process to verify configurations

### Example Attack Scenarios:

* Attacker uses known security flaws in sample applications to compromise server
* Attacker lists directories and finds access control flaw after reverse-engineering code
* Attacker gains access to sensitive info from detailed error messages
* Sensitive data in cloud storage is accessed due to open sharing permissions.

## A03:[2021 - Injection](https://owasp.org/Top10/A03_2021-Injection/)
* Injection vulnerabilities rank 3rd in frequency.
* 94% of applications tested for injection with max rate of 19% and avg rate of 3%, with 274k occurrences.
* Notable CWEs include Cross-site Scripting (CWE-79), SQL Injection (CWE-89), External Control of File Name or Path (CWE-73).
* Vulnerabilities occur when user-supplied data is not validated, filtered, or sanitized, dynamic queries are used without proper escaping, and hostile data is used in ORM search parameters.
* Common injections include SQL, NoSQL, OS command, ORM, LDAP, EL, and OGNL.
* Best way to detect vulnerabilities is through source code review and automated testing of inputs.
* Preventing injection requires keeping data separate from commands and queries and using positive input validation, interpreter-specific escape syntax, and safe APIs.
* Use LIMIT and other SQL controls to prevent mass disclosure of records in case of SQL injection.
