# guideline-http_security_header
These guidelines are mandatory when procuring, setting up and verifying configurations of http security headers on servers

Version: 0.1

#### introduction
- in modern browsers, various protective functions can be activated by setting http response headers, thereby increasing the security level of a web application.
- The following describes the corresponding specifications and recommendations

#### scope
- public web services, websites and applications of the Evangelical Church in Rhineland (EKiR)
- provided by the church itself or by third parties

#### our goals
- organization-wide implementation of http security headers on servers
- limitation to the most important points and comprehensible instructions for action
- our public websites and services shall have a http security header configuration
- future-proof configuration http security headers

#### http security header minimum standard
For the use of http security header, we @ekir refer to the respective applicable version of the 
- TSS-Web Framework, Appendix A: Requirements for HTTP Security Header
- https://secodis.atlassian.net/wiki/spaces/TSSWEB/pages/1015832/Appendix+A+Requirements+for+HTTP+Security+Header

#### implementation
- this minimum standard is intended for general use cases
- the requirements of the tss-web "appendix a: requirements for http security header" must be implemented
- activating a new header should always be combined with comprehensive functional tests
- notice! settings these headers may have implications on the proper functionality of a web application.
- in special individual cases, a deviation from the minimum standard may be appropriate.

#### header audit for public Internet services
tests for websites can be carried out with
- https://securityheaders.com/ (please select "X Hide result")
- https://observatory.mozilla.org ( please select "x Don't include my site in the public results")

#### header evaluator
- https://csp-evaluator.withgoogle.com/
