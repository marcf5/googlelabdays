Lab – Deploy a 3-NIC F5 BIG-IP
-----------------------------------

.. TODO:: Needs lab description

This lab will teach you how to download the |bip| |ve| image to your system.

Task – Deploy a 3-NIC F5 BIG-IP
~~~~~~~~~~~~~~~~~~~~~~~~~
gcloud deployment-manager deployments create marc-multinic-deployment --config /Users/chisinevski/gce/multinic/f5-existing-stack-byol-3nic-bigip.yaml


Task - Set the password for the admin user
~~~~~~~~~~~~~~~~~~~~~~~~~

admin@(localhost)(cfg-sync Standalone)(Active)(/Common)(tmos)# modify auth user admin password

.. TODO:: Needs task description

In this task you will open a web browser and navigate to the |f5| Downloads
site.

.. NOTE:: An account is required to download software.  You can create one at
   https://login.f5.com/resource/registerEmail.jsp

Follow these steps to complete this task:

#. Open your web browser
#. Navigate to https://downloads.f5.com
#. Login with your username and password.
#. After logging in you should see the following window:

   |image1|

Task – Download the Image
~~~~~~~~~~~~~~~~~~~~~~~~~

.. TODO:: Needs task description

In this task we will download the |f5| |bip| |ve| image to your system

Follow these steps to complete this task:

#. Click the 'Find a Download' button.

   .. image:: /_static/image002.png

#. Click the link that contains the |bip| TMOS software version you would like
   to download.

   .. IMPORTANT:: Be sure to click a link that has "\ |ve|" in the name

#. Find the image appropriate for your hypervisor
#. Download the image and save it to you local system

.. |image1| image:: /_static/image001.png
