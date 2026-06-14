# Security Challenge

| File                | Recommended Permission | Reason                                                                              |
| ------------------- | ---------------------- | ----------------------------------------------------------------------------------- |
| password_backup.txt | 600                    | Contains sensitive password information and should only be accessible by the owner. |
| public_notice.txt   | 644                    | Intended for public viewing while allowing modification only by the owner.          |
| system_log.txt      | 640                    | Administrators can modify logs while authorized groups can review them.             |
| personal_notes.txt  | 600                    | Personal information should remain private and accessible only by the owner.        |

## Explanation

password_backup.txt:
Passwords are highly sensitive. Granting access to other users could result in security breaches.

public_notice.txt:
This file contains information meant to be shared. Everyone can read it, but only the owner should modify it.

system_log.txt:
System logs help administrators monitor activity. Users generally do not need write access.

personal_notes.txt:
Personal notes often contain private information and should not be visible to other users.
