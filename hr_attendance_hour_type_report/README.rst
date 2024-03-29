==========================
HR Attendance hours report
==========================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:ce99258fcffd837ed56010390e15c1865cb4ec2585299cfac06d8d5acd4aaef0
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fhr--attendance-lightgray.png?logo=github
    :target: https://github.com/OCA/hr-attendance/tree/14.0/hr_attendance_hour_type_report
    :alt: OCA/hr-attendance
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/hr-attendance-14-0/hr-attendance-14-0-hr_attendance_hour_type_report
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/hr-attendance&target_branch=14.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This module provides a new report in hr_attendance to display the worked time of employees split in
the following categories:

* type of day (weekday, sunday, holiday)
* daytime / nighttime

The information of a day being a holiday comes from the configured public holidays from the module hr_holidays_public.

This is meant as a helper for people interacting with external payroll systems.

**Table of contents**

.. contents::
   :local:

Configuration
=============

There is a new setting in the Attendance settings to set on the company the
hour at which the night worktime starts and ends. The default is from 10pm to
6am.

These hours are expressed in the employee's time zone.

Usage
=====

Go to Attendances -> Attendances for Payroll, you will see a list view or a pivot view of attendances with the following values:

* date (using the check in datetime, converted to the date in the employee's timezone
* date type (normal, sunday or holiday)
* daytime work duration
* nighttime work duration
* total work duration

The list view and pivot view can be exported to a spreadsheet for further processing.

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/hr-attendance/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/hr-attendance/issues/new?body=module:%20hr_attendance_hour_type_report%0Aversion:%2014.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
~~~~~~~

* Camptocamp

Contributors
~~~~~~~~~~~~

* Alexandre Fayolle <alexandre.fayolle@camptocamp.com>

Maintainers
~~~~~~~~~~~

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/hr-attendance <https://github.com/OCA/hr-attendance/tree/14.0/hr_attendance_hour_type_report>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
