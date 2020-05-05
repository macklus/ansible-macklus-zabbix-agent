Ansible Zabbix agent Role
=========================

Install and configure Zabbix Agent

Role Variables
--------------

    macklus:
      zabbix:
        agent:
          pidfile
          logfile
          logfilesize
          debuglevel
          sourceip
          enableremotecommands
          logremotecommands
          server
          listenport
          listenip
          startagents
          serveractive
          hostname
          hostnameitem
          hostmetadata
          hostmetadataitem
          hostinterface
          hostinterfaceitem
          refreshactivechecks
          buffersend
          buffersize
          maxlinespersecond
          timeout
          allowroot
          user
          unsafeuserparameters
          tlsconnect
          tlsaccept
          tlscafile
          tlscrlfile
          tlsservercertissuer
          tlsservercertsubject
          tlscertfile
          tlskeyfile
          tlspskidentity
          tlspskfile
          tlsciphercert13
          tlsciphercert
          tlscipherpsk13
          tlscipherpsk
          tlscipherall13

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
        - macklus.zabbix-agent

License
-------

GPL-3.0-only