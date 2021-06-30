Release Notes
==============

.. rst-class:: release-notes-table

.. list-table:: 
    :widths: 18 10 72
    :header-rows: 1

    * - Release date
      - Version
      - Notes
    * - 2021/05/31
      - 1.5.1	
      - - Launched IDE Services, supports frameworks including Hyperledger Fabric, FISCO BCOS, Ethereum, Nervos and Algorand.
    * - 2021/04/28	
      - 1.5.0	
      - - Iterative optimization and technical optimization of the BSN international website (`www.bsnbase.io <https://www.bsnbase.io>`__) to enhance user experience.
        - Launched BSN dedicated node services based on ConsenSys Quorum framework.
        - Launched the commercial service of Interchain Communications Hub based on IRITA.
        - Fixed some bugs and enhanced the stability of the system.
    * - 2021/03/19
      - 1.4.1	
      - - Added public chain main net and test net nodes along with native API access services. Including: Casper, Findora and Near.
    * - 2021/01/31
      - 1.4.0	
      - - Iterative optimization and technical optimization of the BSN international website (`www.bsnbase.io <https://www.bsnbase.io>`__) to enhance user experience.
        - Launched the commercial service of Interchain Communications Hub based on Poly Enterprise.
        - Fixed some bugs and enhanced the stability of the system.
    * - 2020/11/30
      - 1.3.1	
      - - Added public chain main net and test net nodes along with native API access services. Including: BTY, Oasis and Polkadot.
    * - 2020/10/31
      - 1.3.0
      - - Optimized the BSN International website (`www.bsnbase.io <https://www.bsnbase.io>`__) to improve user experience.
        - Launched BSN Permissioned Blockchain Testnet, providing developers with a free testing environment supporting:Hyperledger Fabric R1, FISCO BCOS K1 DApp Services publication.
        - Interchain testing services: Launched the BSN Interchain Communications Hub on BSN Testnet based on Poly Enterprise and IRITA.
        - Added the BSN empowerment platform APIs to allow third-party portals to access BSN Permissionless Services.
        - Added the TPD (Transactions Per Day) limit control function in the Permissionless Services.
        - Fixed some bugs and enhances the stability of the system.
    * - 2020/9/24
      - 1.2.1
      - - Updated the BSN Global website address to (`www.bsnbase.io <https://www.bsnbase.io>`__).
        - Added public chain main net and test net nodes along with native API access services. Including: Algorand, ShareRing and Solana.
        - Added Enable Key function in the public chain project.
    * - 2020/8/10
      - 1.2.0	
      - - Redesigned the user interface toprovide better navigation and user experience.
        - Added public chain main net and test net nodes along with native API access services. Including: Nervos, Neo, ETH, Tezos, EOS, IRISnet, etc.
        - Added commercial functionality for Hyperledger Fabric and FISCO BCOS frameworks.
        - Updated FISCO BCOS framework to support SECP256 K1 encryption algorithm.
        - Added the following functionality to Permissioned services: recurring payment mechanism for service charge and data usage charge, service configuration upgrade.
        - Added Permissionless service plan purchase and upgrade.
        - Added "My Account" in User Center to make it easier for users to update credit card information, check bills, pay bills and download invoices (we process all credit card activities directly on Stripe).
        - Added Online Help Manual to provide developers and portal users easy-to-follow instructions.
        - Added PCN gateway SDK and all examples on Github: https://github.com/bsnda.
        - Fixed a few bugs to enhance the stability of the system.
    * - 2020/4/25
      - 1.1.0
      - - The BSN global portal has officially launched. Beta testing will be held from April 25th, 2020 to June 25th, 2020.
        - Developers can deploy one three-peer DApp (service) at up to three public city nodes (PCNs) free of charge during beta testing.
        - There is a total of 10 available PCNs during beta testing. They are deployed on AWS, Microsoft Azure, Google Cloud, China Mobile Cloud, and Huawei Cloud.
        - During beta testing, there are two frameworks to choose from, Hyperledger Fabric V1.4.3 or FISCO BCOS V2.4.0.
        - Developers can choose “Key Trust Mode” or “Public-Key Upload Mode” to manage their service users’ certificates and keys.
        - Basic information and chaincode/smart contracts in deployed services can be modified anytime. PCNs, however, cannot be changed once chosen.
        - Published services are private by default. Developers will need to apply for a public listing. After approval, they will be available on the App Store.
        - Developers will need to grant permissions to other users to participate in their services. The participants then follow the services’ instructions to generate service access keys and user transaction keys by using either “Key Trust Mode” or “Public-Key Upload Mode”.
        - The PCN gateway provides a set of user registration APIs for deployed services. Developers can register service users via these APIs from their off-BSN systems. Developers do not need to log in to the BSN global portal.
        - The PCN gateway APIs support “Key Trust Mode” for both Fabric and FISCO BCOS. “Public Key Upload Mode” is only supported for Fabric.
        - For more info on gateway APIs, please refer to the developer’s manual.


