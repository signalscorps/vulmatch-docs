---
description: Learn more about managing Vulmatch Groups and Users.
---

# Group Management

## Groups

### Group Management

Each user belongs to a Group. A user can only belong to one group.

Each Group has one Group Admin. By default this is the creator of the Group, however, ownership can be reassigned to any active Member of the Group.\\

| Function                               | Admin | Member |
| -------------------------------------- | ----- | ------ |
| Invite new members to Group            | TRUE  | FALSE  |
| Delete existing Members from the Group | TRUE  | FALSE  |
| Edit Members Permissions in the Group  | TRUE  | FALSE  |
| View all Members in Groups             | TRUE  | TRUE   |

![Vulmatch group management](<../.gitbook/assets/vulmatch-group-management (1).png>)

Use the Group Management page for this: [https://app.vulmatch.com/user/manage\_group](https://app.vulmatch.com/user/manage\_group)

### Group Plans

Each Group has a plan. By default, the free plan is assigned at sign up. Any user of the group can request a plan upgrade.

You can see a current list of plans and their restrictions here: [https://www.vulmatch.com/pricing/](https://www.vulmatch.com/pricing/)

## Users

### User Permissions

There are two user permissions available, read and read/write. You can see what functions are available for each permission type below:

| Function                                | Read | Read/write |
| --------------------------------------- | ---- | ---------- |
| View CVE                                | TRUE | FALSE      |
| View product stack                      | TRUE | TRUE       |
| Add/edit product stack                  | TRUE | FALSE      |
| View alerts                             | TRUE | TRUE       |
| Add/edit alerts                         | TRUE | FALSE      |
| Generate API key (if supported in plan) | TRUE | TRUE       |

### User Security

Two-factor authentication to all users. It is strongly recommended that all users configure two-factor authentication.

{% hint style="info" %}
A 10% discount will be applied on Group Plans where all members have two-factor authentication enabled.
{% endhint %}

Group admins can view which of their Group Members have two-factor authentication enabled on the Group Management page: [https://app.vulmatch.com/user/manage\_group](https://app.vulmatch.com/user/manage\_group)

### Delete user

A user or group admin can delete a members account.

A user can do this on the "My Profile" page. Group admins can do this from the "Group Management" page.

Deleting an account will delete that Members personal information (inc. API keys) but any content created by the Member (e.g. Alerts) will remain available to the Group
