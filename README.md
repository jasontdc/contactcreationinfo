# contactcreationinfo

![Screenshot](/images/screenshot.png)

This is a simple CiviCRM extension that saves the current user and current server time to custom fields when creating a new contact.

CiviCRM already has a Change Log; however, it is not possible to report on this information via the built-in Contact Reports within CiviCRM.

Because this extension saves the current user and time when a contact is created in simple Custom Fields within CiviCRM, users can report on this information using Contact Summary and Contact Detail reports.

The extension is licensed under [MIT](LICENSE.txt).

## Requirements

* PHP v7.4+
* CiviCRM (*FIXME: Version number*)

## Installation (Web UI)

Learn more about installing CiviCRM extensions in the [CiviCRM Sysadmin Guide](https://docs.civicrm.org/sysadmin/en/latest/customize/extensions/).

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl contactcreationinfo@https://github.com/FIXME/contactcreationinfo/archive/master.zip
```
or
```bash
cd <extension-dir>
cv dl contactcreationinfo@https://lab.civicrm.org/extensions/contactcreationinfo/-/archive/main/contactcreationinfo-main.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/FIXME/contactcreationinfo.git
cv en contactcreationinfo
```
or
```bash
git clone https://lab.civicrm.org/extensions/contactcreationinfo.git
cv en contactcreationinfo
```

## Getting Started

(* FIXME: Where would a new user navigate to get started? What changes would they see? *)

## Known Issues

(* FIXME *)
