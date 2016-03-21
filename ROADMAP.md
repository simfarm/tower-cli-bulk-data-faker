## Features to add

 - Indepodent creation of data
   - that is, creating enough to satisfy a total quota, instead of creating
     the number the user specifies
 - Point-Of-View teams
   - this needs to link to a Point-Of-View user in order to stress RBAC correctly
 - Smarter fake data creator, giving convincing names for
   - projects
   - hosts
   - credentials
   - teams
   - job templates
     - Leverage Galaxy to provide data to do this with?
 - A command to migrate local credentials to Tower
 - A command to migrate local Ansible host files to Tower 

## Packaging and Collaboration

 - Command line packaging
 - Travis tests
 - PiPy package
   - Probably as a separate package (too dangerous for tower-cli inclusion)