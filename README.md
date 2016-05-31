#nagios3-learning

##configuration components
- Main config file (ex: /etc/nagios3/nagios.cfg) contains
  - Resource files (ex: /etc/nagios3/resource.cfg)
  - Object definition files (ex: /etc/nagios3/conf.d/*.cfg)
    - Services
    - Service Groups
    - Hosts
    - Host Groups
    - Contacts
    - Contact Groups
    - Commands
    - Time Periods
    - Notification Escalations
    - Notification and Execution Dependencies 

- CGI file (ex: /etc/nagios3/cgi.cfg) references
  - Main config file
