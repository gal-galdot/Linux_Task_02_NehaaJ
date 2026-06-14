# Permission Analysis

## 755

Owner Rights:

* Read
* Write
* Execute

Group Rights:

* Read
* Execute

Other User Rights:

* Read
* Execute

Use Case:
Commonly used for directories and executable scripts where the owner can modify files but others can only access and run them.

---

## 644

Owner Rights:

* Read
* Write

Group Rights:

* Read

Other User Rights:

* Read

Use Case:
Used for configuration files, documents, and web files that should be readable by everyone but editable only by the owner.

---

## 777

Owner Rights:

* Read
* Write
* Execute

Group Rights:

* Read
* Write
* Execute

Other User Rights:

* Read
* Write
* Execute

Use Case:
Rarely recommended. Useful only for temporary testing environments because it allows every user full access.

---

## 600

Owner Rights:

* Read
* Write

Group Rights:

* No Access

Other User Rights:

* No Access

Use Case:
Suitable for passwords, SSH keys, and confidential files.

---

## 700

Owner Rights:

* Read
* Write
* Execute

Group Rights:

* No Access

Other User Rights:

* No Access

Use Case:
Used for private directories, personal scripts, and administrator-only resources.
