# Incident INC-002 - Application Login Failure

## Incident ID

INC-002

## Issue Summary

User reports they are unable to log into internal business applications after a recent password reset.

## System / Application

Internal business systems, Microsoft 365 authentication

## User / Location

Office-based users working remotely

## Impact & Urgency

User is unable to access applications required for daily work. Single user impact with normal business priority.

## Initial Checks Performed

- Verified the users identity
- Confirmed password reset has completed sucessfully
- Check users account status was active and not locked/ disabled
- Confirm no reported service outage

## Actions Taken

- Guided user to sign out of the application and Microsoft 365
- Confirmed user signed back in using updated credentials
- Asked user to retry login after authentication refresh

## Escaltion Decision

Resolved at first line. Issue related to cached credentials follwoing password reset.

## Resolution

User successfully logged into the application after authentication was refreshed.

## Post-Incident Notes / Prevention

Advise users to fully sign out of application and devices after passwrod changes to prevent authentication issues.
