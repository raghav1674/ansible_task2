Role Name
=========

webserver

Requirements
------------

Redhat OS


Role Variables
--------------


conf_file: raghav
document_root_folder: "/var/www/raghav"
git_url: "https://raw.githubusercontent.com/raghav1674/devopstask3/master/index.html"
http_port: 81


Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: ec2
      roles:
      - role: webserver

License
-------

BSD

Author Information
------------------
Raghav Gupta
