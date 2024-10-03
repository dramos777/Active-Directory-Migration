# Active-Directory-Migration
This article will guide you through a successful migration from Active Directory on Windows to SAMBA, and then from SAMBA back to Windows.

For several days, I spent time researching how to address a custom problem I faced, encountering significant difficulty in finding a solution. Information about this process is not easy to come by. So let's go!

First, let’s take a look at the scenario:

    DC1: Current Active Directory Server (Windows Server 2022 Standard)
    DK1: Desktop for testing login, Group Policy Objects (GPO), and trust relationships throughout the process (Windows 10 Pro)
    DC2: SAMBA Server for migration from Windows (UCS Univention Latest)
    DC3: Temporary Active Directory Server for migration from SAMBA (Windows Server 2022 Standard)
    SAMBA-TOOL: SAMBA Server that will be used to migratre FSMO between servers
    DC4: New Primary Active Directory Server for migration from the Temporary Server (Windows Server 2022 Standard)
    DC5: Backup Active Directory Server (Windows Server 2022 Standard)

...IN DEVELOPMENT...
