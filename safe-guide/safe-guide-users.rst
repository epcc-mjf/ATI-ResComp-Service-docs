Individual Users
================

The `ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_ is an online user
service management system. Through the ATI SAFE, individual users can request
machine accounts, reset passwords, see available resources and track
their usage. All users must be registered on the ATI SAFE before they can apply
for accounts on the machines in the ATI Research Computing Service.

Registering, logging in, passwords
----------------------------------

How to register on the ATI SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Go to the ATI SAFE `New User Signup
   Form <https://safe.epcc.ed.ac.uk/ati/signup.jsp>`__
   
#. Fill in your personal details. You can come back later and change
   them if you wish
#. Click "Register"
#. You are now registered. Your ATI SAFE password will be emailed to the
   email address you provided. You can then login with that email
   address and password

At this point your account is registered on the ATI SAFE but you do not
have a machine account on the ATI Service.

To obtain a machine account on the ATI Service you require a 
*Project Code*. Your project's PI or Project Manager should be able to
supply you with these details. Once you have them you should:

#. Log into the ATI SAFE (see `How to login to the ATI SAFE`_)
#. Request machine account (see `How to request an account for an ATI Research Computing Service machine`_).

.. _login:

How to login to the ATI SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Go to the  ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_ 

#. Type in the email address you have registered with.
#. Type in your ATI SAFE password.
#. Click "Login".
#. You are now on the Main Page and here you can see Menus along the top
   which give access to SAFE functionality.

How to change your personal details on ATI SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to the ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_. Then:

#. Go to the Menu *Your details* and select *Update personal details*
#. Make the changes you wish
#. Click *Commit Update* to save the changes
#. Go back to *Your details* and you will see the revised information

Do not forget the last step, or nothing will happen. Note that your
postal address does not automatically include the name of your
department and institution; if you want these in your postal address,
you must type them again.

How to change your email address on ATI SAFE
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to the ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_. Then:

#. Go to the Menu *Your details* and select *Update email*
#. Enter the new email address and click *Request*

A verification email will then be sent to the new email address. This
email contains a link which you must use to verify your new address. On
acknowledging your new address the change will be committed and you must
use the new email address when logging into ATI SAFE.

How to change your ATI SAFE password
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to the ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_. Then:

#. Go to the Menu *Your details* and select *Change SAFE password*
#. Fill in the boxes and click *Change*

How to reset your ATI SAFE password
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to the ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_. Then:

#. Enter your email address
#. Click *Email*
#. The ATI SAFE will mail your password to your email address.

SAFE will only mail to email addresses it already knows. But email is
not a secure medium, so if you change your password this way, you should
immediately change it again from inside the SAFE. 

Of course, anyone could go to SAFE, type your email address and request
a new password by clicking "Email". If that happens you will receive an
email message out of the blue saying that your password has been
changed. In this case you should certainly change your password again.

How to request an account for an ATI Research Computing Service machine 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to the ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_. Then:

#. Go to the Menu *Login accounts* and select *Request login account*
#. Choose the project code for the machine you want from the *Project* pull-down list.
#. Then press *Select Project*. A new screen will appear.
#. Press the radio button next to the machine you want the account 
   for then press  *Select Machine*.
#. In the field next to *Request username*, enter the username you would prefer to use on this service machine.

   Every username must be unique, and you must create a new machine
   account with a unique username for each project you work on.
   Usernames cannot be used on multiple projects, even if the previous
   project has finished.

Next you will be asked to accept the Terms and Conditions of
Access by clicking the appropriate button. When you do this, you will be sent an
acknowledgment by email, which will include your ATI SAFE password— you
should change this as soon as possible. 

Now you have to wait for your PI or project manager to accept your
request to register. When this has happened, the systems team are
prompted to create your account on the service machine. Once this has
been done, you will be sent an email. You can then `pick up your
password <#getpass>`_ 
for the service machine from your SAFE account.

.. _getpass:

How can I pick up my password for the service machine?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Wait till you receive the email with your details. Then:

#. `Login to SAFE <#login>`__.
#. Go to the Menu *Login accounts* and you will see your account on the
   service machine listed. Click *username*
#. This will display details of your account. Click *View Login Account
   Password* You will need to enter in your SAFE password and then click
   *view*, and you will see your password to the service machine

This password is generated randomly by the software. It's best to
copy-and-paste it across when you log in to the service machine.


How to reset a password on your machine account
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

If you have forgotten your current password, or it has expired, then you
can ask for it to be reset:

`Login to SAFE <#login>`__. Then:

#. Go to the Menu *Login accounts* and select the account you need the
   new password for
#. Click *username* which displays details of this service machine
   account.
#. Click *New Login Account Passwd*

Now the systems team will change your password. When this has been done,
you will be informed by email; this means that you can come back to SAFE
and `pick up your new password <#getpass>`__.

How to change a password on your machine account
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

This is machine-specific.

**hydra-vpn.epcc.ed.ac.uk gateway**:

1. At the command-line, run::

    passwd

2. You will be prompted to enter your old password.
3. You will be prompted to enter your new password twice.

**ATI Cray Urika**:

1. At the command-line, run::

    change_ldap_passwd

2. You will be prompted to enter your new password twice.
3. You will be prompted to enter your old password.

**Note:** When you change your password on machines in this way, the changes are NOT reflected on the SAFE, so please remember your new password.

User Mailing Options
--------------------

How to view user mailings
~~~~~~~~~~~~~~~~~~~~~~~~~

| All mailings are archived and can be viewed in
  `ATI SAFE <https://safe.epcc.ed.ac.uk/ati>`_.
| Please `login to SAFE <#login>`__ and go to the section *View user
  mailings*. Press the *View* button to access the mailings.

How to get added to, or removed from the email mailing list?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

There are three mailing list options available.

-  The *Major Announcements* mailings will contain information on major
   service upgrades and future plans. This option is enabled for all
   users by default.
-  The *Service News* mailings will contain information on training
   courses, newsletters, events, and other general announcements. This
   option is enabled for all users by default.
-  The *System Status Notifications* will inform users when the service
   goes up or down, including the reminders of the next planned
   maintenance shutdowns. This option is not enabled by default, those
   wishing to receive this information will need to explicitly subscribe
   to it.

Any combination of these three options may be selected via SAFE:

#. `Login to SAFE <#login>`__.
#. Go to the Menu *Your details* click *Email list settings*
#. In the panel headed *Mailing list preferences* click on the options
   you would like to subscribe to.
#. Click *Update List Preferences*

**Note 1:** There is an option to unsubscribe from the user mailings
completely, which overrides any option enabled in *Mailing list
preferences* panel.

#. Click on the Menu *Your details* click *Update personal details* find
   *Opt out of user emails* field and click it
#. Click *Commit Update*

Do not forget the last step, or nothing will happen.

**Note 2:** Regardless of whether you are subscribed to a particular
mailing list, you can still view ALL user mailings which have been sent,
in SAFE. See `here <#mailings>`__ for details.

| 

Tracking and Managing Available Resources
-----------------------------------------

How to check how much time and space are available to you
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <#login>`__ and Go to the Menu *Login accounts*, select
the *username* which you wish to see details for. You will then see the
information for this account. You will see the quotas for the disk space
(if the project group is using these) and how much is in use. You can
also see which file systems your project is using. Under the heading
'Volume' you will see entries for RDF (if used by your project), home
and work and in brackets after each, the name of the filesystem they are
hosted on, followed by the current usage by your project, and total
quota.

The budget values displayed are updated every morning, and the values
shown for disk use are updated four times a day. For this reason, all
these values may not be completely up-to-date. If there is a lot of
activity in your project, the numbers shown could be significantly
different from from the current ones.

How to request more kAUs/disk space
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In the first instance, please contact the principal investigator, or the
project manager of your project. The PI will then take the necessary
steps to either allocate you more resources out of the project reserve,
or to request an increase from the helpdesk/research councils.

The helpdesk does not own project resources and has no authority to
allocate them to individual users. This responsibility lies with the
project PI/project manager.

How to review the use you have made of the service, or the activity of the service as a whole
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <#login>`__. Then:

#. Go to the Menu *Service information* and select *Report Generator*
#. Select the report you wish to run and the format you want the output
   in (web, PDF, CSV, XML) by clicking the appropriate icon in the list.
#. Complete the required information in the form: this will usually
   consist of at least a date range to analyse and may have other
   options depending on the report you are running.
#. Click *Generate Report*

If you are a PI or Project Manager, you will have access to additional
reports to generate information on whole projects or groups as well as
your own usage and the usage of the service as a whole.

| 

Miscellaneous
-------------

How to check the queries you have submitted to the helpdesk
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <#login>`__. Then:

#. Go to the Menu *Help and Support* and select *Your support requests*
#. Click the number of a query to check the contents of the query log

This will show you the queries of yours that haven't yet been resolved.
Note that some of the internal correspondence about a query will not be
shown. You can also use SAFE to submit a query—use *New support
request*.

How to register your approval — or your annoyance
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

`Login to SAFE <#login>`__. Then:

#. Go to the Menu *Help and Support* and select *Service feedback*
#. Click on the scale somewhere between 5 penalty points and 5 gold
   stars indicating your level of anger or delight.
#. Optionally: enter a comment in the comment box.
#. Click *Set Token*

The tokens may appear in the public service reports, although your name
will not be published with them. Although an entry in the comment field
is optional, it necessarily gives greater weight to your
feelings—without it we cannot tell why you have set a token.

|
