Role: cns.ec2-vpc-peer
========

Request and accept VPC peering request between two AWS accounts

Requirements
------------

Nothing, it runs out of the box.

Role Variables
--------------

In the current version, you can specify the following variables:

| Name     | Default |                                 |
|----------|---------|---------------------------------|
| profile  |   ---   | Primary AWS credentials profile |
| mgmt_profile | --- | Management AWS credentials profile |
| mgmt_net | --- | Management VPC network (e.g. 10.0.1.0/24) |

Dependencies
------------

This package has no dependencies.

License
-------

GPLv2

Author Information
------------------

* Sam Morrison

Examples
--------
```yaml
---
- name: cns.ec2-vpc-peer role test
  hosts: all
  roles:
    - cns.ec2-vpc-peer
```
