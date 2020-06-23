# ACL

## Access Controls

#### Access Controls are the selective restriction of resources. Access Controls are implemented everywhere in computer systems. UNIX files have read, write, and execute permissions assigned to owners, groups, and everyone else. Websites have limited access to pages based on the credentials of a user. APIs restrict access to internal and external developers differently.

## Backend API Layer

- manage login cycle
- maintain user db
- maintain each user
- authenticate users
- create/manage/apply role based controls
- maintain and reference capabilities, based on role
- restrict acc to features based on capabilties (such as routes)
- middleware used to control routes
- mongoose middleware/hooks to restrice access to business logic
