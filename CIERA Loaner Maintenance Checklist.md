# CIERA Loaner Maintenance Checklist

## Accounts
All loaners should have the following accounts:

**CIERA Administrator**
Shortname: cieraadmin
Password: [Redacted]

**CIERA User**
Shortname: ciera
Password: [Redacted]

The **CIERA Administrator** account is an administrator account shared across all of the loaners and the credentials should only be given to IT personnel. All temporary users should be given access only to the **CIERA User** account. If sudo access is required, the user may be given a temporary account which will be deleted when the computer is returned.

When computers are returned, the user's data should be deleted by removing the **CIERA User** account, selecting the option for secure deletion of the home folder, and then re-creating it prior to issuance to the next user. If the user has had any temporary accounts created for them, these accounts should also be deleted with the secure erase option, but should not be re-created.

## Software
All loaners should have the latest supported versions of the following software installed:

 - Microsoft Office
 - Mozilla Firefox
 - Google Chrome
 - Java

## CIERA NetID
All loaners should access the **Northwestern** network from the **CIERA Administrator** account using the following credentials:

NetID: ccf548
Password: [Redacted]

## CIERA Apple ID
All loaners should access the App Store from the **CIERA Administrator** account using the following credentials:

Email: ciera@northwestern.edu
Password: [Redacted]

## System Updates
All loaners should have the latest system updates from Apple. These can be obtained by running `sudo softwareupdate -i -a` at the terminal from the **CIERA Administrator** account.

## App Store Software
App store software not installed using the CIERA Apple ID should be removed if it cannot be updated by dragging the appropriate application from the Applications folder to the Trash and emptying the trash. App store software and updates installed using the CIERA Apple ID should be kept up to date.

## Plugin Check
The Mozilla Plugin Check should be run from within Firefox to ensure all plugins are up to date. Any out-of-date plugins should be updated.

## A Note on Passwords
Passwords listed in this document as [Redacted] are considered non-public information and should be obtained from John Everett in Tech F232.

## Loaner Use Policies
Users should not have possession of a loaner for longer than four weeks during the academic year or for longer than a single research term during the summer quarter, and should take steps to ensure they have a personal computer of their own before the end of that time period. IT personnel issuing loaners are required to inform users of this policy and to keep track of which users were issued which loaners on which date.

Users are required to keep copies of any data they desire to keep from their loaners before returning them. Once a loaner is returned to the department, no data on it is guaranteed to be kept for any amount of time. IT personnel are required to inform users of this policy at the time when the loaner is issued and again when it is returned. Failure of users to comply with this policy may result in permanent loss of user data.