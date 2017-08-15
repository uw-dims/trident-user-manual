.. _introduction:

Introduction 
============

This document is called the "Trident User Manual" because it is focused on the
daily operational aspects of using a Trident portal in the context of trust
group activities. It is thus focused on "user" activities, not "system administration"
activities.  There are some terms that will be used in this document and that
form the basis for how it is structured:

* A **trust group** (also known as a "TG" for short), is an operational
  concept of the Trident portal that includes users who are **trust group
  administrators** and/or **trust group members**.  These are all portal
  users, so the term "users" is too vague to be useful. Details on TG
  formation and operation are covered in :ref:`trust_groups`.

* A **trust group administrator** is someone who has leadership responsibility
  for handling the membership details and overall organization of information
  in a Trident portal system. Things that TG admins need to know are found
  in :ref:`trust_group_admin`.
 
* A **trust group member** is someone who is a member of a given trust group.
  (There may be more than one trust group, but you can only be active in
  one trust group at a time, so the focus will always be on "the active trust
  group.") Information about using the portal for TG members is covered in
  :ref:`trust_group_user`.

* Finally, there are also **portal administrators** who have access to the
  ``trident`` account, which is the primary account for controlling the
  entire portal. They are also sometimes called **site administrators**.
  (They may or may not be the same as the **system administrators**, who
  have full access to the operating system underlying the Trident portal.
  The system administrators are the ones who manage the Ansible variables and
  run the Ansible playbooks described in the
  :ref:`ansible_dims_playbooks:ansible_dims_playbooks` document.)
