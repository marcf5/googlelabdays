Getting Started
---------------

.. TODO:: Complete getting started instructions

Please follow the instructions provided by the instructor to start your
lab and access your jump host.

.. NOTE::
	 All work for this lab will be performed exclusively from the Windows
	 jumphost. No installation or interaction with your local system is
	 required.

Lab Topology
~~~~~~~~~~~~

.. TODO:: Complete lab topology

The following components have been included in your lab environment:

- 2 x F5 BIG-IP VE (v12.1)
- 1 x F5 iWorkflow VE (v2.1)
- 1 x Linux LAMP Webserver (xubuntu 14.04)
- 1 x Windows Jumphost

Lab Components
^^^^^^^^^^^^^^

.. TODO:: Complete lab components table

The following Google Cloud VPC Networks and subnets are already created and will be used when deploying F5 BIG-IPs.

.. list-table::
    :widths: 20 40 40 40
    :header-rows: 1
    :stub-columns: 1

    * - **Component**
      - **VPC network name**
      - **Subnet name**
      - **IP address range**  
    * - External VPC Network
      - - marc-bigip-ext
      - - marc-subnet-ext
      - - 10.10.1.0/24
    * - Management VPC Network
      - - marc-bigip-mgmt
      - - marc-subnet-mgmt
      - - 10.0.2.0/24  
    * - Internal VPC Network
      - - marc-bigip-int
      - - marc-subnet-int
      - - 10.0.3.0/24


