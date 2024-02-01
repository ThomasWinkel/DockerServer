Docker stacks, using a central nginx reverse proxy to manage external accessibility.

Characteristics:
* Only reverse proxy opens ports to the internet
* Reverse proxy manages https certificates for all services
* https forwarding for all http requests.

Stacks:
* LAMP Template
* Redmine
* Gitlab
* Simple Machines Forum
