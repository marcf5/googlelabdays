Lab – Deploy a 3-NIC F5 BIG-IP
-----------------------------------

.. TODO:: Needs lab description

This lab will teach you how to deploy and configure F5 BIG-IP in Google Cloud.

Task – Deploy a 3-NIC F5 BIG-IP
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
gcloud deployment-manager deployments create marc-multinic-deployment --config f5-existing-stack-byol-3nic-bigip.yaml


Task - Set the password for the admin user
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

admin@(localhost)(cfg-sync Standalone)(Active)(/Common)(tmos)# modify auth user admin password

Examples - possible architectures

        .. IMPORTANT:: F5 BIG-IP detailed picture

           |bipdetai|


.. |bipdetai| image:: https://github.com/marcf5/googlelabdays/raw/develop/docs/_static/f5bigipdetailedpicture.png
