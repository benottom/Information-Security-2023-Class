# h2 Goat
Starting with the instructor statement to keep it secure, compliant and moral. Make a good point to state - while learning ethical hacking - to NOT attempt any actions on machines you don't possess.
# OWASP: [OWASP 10 2021](https://owasp.org/Top10/)

## A06:[2021 - Vulnerable and Outdated Components](https://owasp.org/Top10/A06_2021-Vulnerable_and_Outdated_Components/)

## A05:[2021 - Security Misconfiguration](https://owasp.org/Top10/A05_2021-Security_Misconfiguration/)

## A03:[2021 - Injection](https://owasp.org/Top10/A03_2021-Injection/)
* Injection vulnerabilities rank 3rd in frequency.
* 94% of applications tested for injection with max rate of 19% and avg rate of 3%, with 274k occurrences.
* Notable CWEs include Cross-site Scripting (CWE-79), SQL Injection (CWE-89), External Control of File Name or Path (CWE-73).
* Vulnerabilities occur when user-supplied data is not validated, filtered, or sanitized, dynamic queries are used without proper escaping, and hostile data is used in ORM search parameters.
* Common injections include SQL, NoSQL, OS command, ORM, LDAP, EL, and OGNL.
* Best way to detect vulnerabilities is through source code review and automated testing of inputs.
* Preventing injection requires keeping data separate from commands and queries and using positive input validation, interpreter-specific escape syntax, and safe APIs.
* Use LIMIT and other SQL controls to prevent mass disclosure of records in case of SQL injection.
