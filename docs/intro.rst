Getting Started
---------------

.. TODO:: Complete getting started instructions

Please follow the instructions provided by the instructor to start your
lab and access your jump host.

Lab Topology
~~~~~~~~~~~~

.. TODO:: Complete lab topology


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

In the next section, we'll use the Google Deployment Manager template at https://github.com/marcf5/googlelabdays/blob/develop/f5-existing-stack-byol-3nic-bigip.yaml to deploy a 3-NIC F5 BIG-IP on the VPC networks and subnets above.
