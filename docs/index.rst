**ACES**
================

**ACES Quickstart Guide**
-------------------------
Deployed and in Friendly User Mode

**ACES Usage Policy**
---------------------
Access to ACES is granted with the condition that you will understand and adhere to all TAMU HPRC and ACES-specific policies.

General policies can be found on the HPRC `Policies <https://hprc.tamu.edu/policies/>`_ page.

**Acessing ACES**
-----------------
Most access to ACES is done via a secure shell session. In addition, two-factor authentication is required to login to any cluster.

Users on Windows computers use either PuTTY or MobaXterm. If MobaXterm works on your computer, it is usually easier to use. When starting an ssh session in PuTTY, choose the connection type 'SSH', select port 22, and then type the hostname 'aces.hprc.tamu.edu'. For MobaXterm, select 'Session', 'SSH', and then remote host 'aces.hprc.tamu.edu'. Check the box to specify username and type your NetID. After selecting 'Ok', you will be prompted for Duo Two Factor Authentication. For more detailed instructions, visit the Two Factor Authentication page.

Users on Mac and Linux/Unix should use whatever SSH-capable terminal is available on their system. The command to connect to ACES is as follows. Be sure to replace [NetID] with your TAMU NetID.

.. code-block:: php
  
  [user1@localhost ~]$ ssh [NetID]@aces.hprc.tamu.edu

.. note::
  
   Note: In this example [user1@localhost ~]$ represents the command prompt on your local machine. 
   
Your login password is the same that used on Howdy. You will not see your password as your type it into the login prompt.
  
