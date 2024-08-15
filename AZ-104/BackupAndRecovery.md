# Backup and Recovery Abbreviations
- BCDR  : Business Continuity and Diaster Recovery
- RPO   : Recovery Point Objectives
- RTO   : Recovery Time Objectives
- DPM   : System Center Data Protection Manager 
- MABS  : Microsoft Azure Backup Server
- MARS  : Microsoft Azure Recovery Services 
- LTR   : Long-Term Retention

#

- [Zero-Infrastructure Backup](https://learn.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/backup-restore?view=azuresql#azbackup) : You do not have to manage backup servers or storage locations.
Scale: Protect many SQL VMs and thousands of databases.
- [MARS](https://learn.microsoft.com/en-us/azure/backup/install-mars-agent#about-the-mars-agent) : Azure Backup uses the MARS agent to back up files, folders, and system state from on-premises machines and Azure VMs. Those backups are stored in a Recovery Services vault in Azure. 
- [MABS](https://learn.microsoft.com/en-us/azure/backup/backup-azure-microsoft-azure-backup) : With Azure Backup Server, you can protect application workloads, such as Hyper-V VMs, VMware VMs, Azure Stack HCI VMs, Microsoft SQL Server, SharePoint Server, Microsoft Exchange, and Windows clients from a single console.