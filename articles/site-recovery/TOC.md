# Overview
## [What is Site Recovery?](site-recovery-overview.md)
## [How does Site Recovery work?](site-recovery-azure-to-azure-architecture.md)
## [How does Hyper-V replication to Azure work?](site-recovery-hyper-v-azure-architecture.md)
## [What workloads can you protect?](site-recovery-workload.md)
## [Site Recovery support matrix](site-recovery-support-matrix-azure-to-azure.md)
## [FAQ](site-recovery-faq.md)
## [Watch an introduction](https://azure.microsoft.com/resources/videos/index/?services=site-recovery)

# Get Started
## [Replicate Azure virtual machines (preview)](site-recovery-azure-to-azure.md)
## [Replicate VMware VMs to Azure](site-recovery-vmware-to-azure.md)
## [Replicate physical servers to Azure](site-recovery-physical-servers-to-azure.md)
## [Replicate Hyper-V VMs to Azure (with VMM)](site-recovery-vmm-to-azure.md)
## [Replicate Hyper-V VMs to Azure](site-recovery-hyper-v-site-to-azure.md)
## [Replicate Hyper-V VMs to a secondary site (with VMM)](site-recovery-vmm-to-vmm.md)
## [Replicate VMware VMs and physical servers to a secondary site](site-recovery-vmware-to-vmware.md)
## [Replicate VMware VMs to Azure in a multi-tenant deployment (CSP)](site-recovery-multi-tenant-support-vmware-using-csp.md)

# How To
## Plan
### [Prerequisites for Azure replication](site-recovery-azure-to-azure-prereq.md)
### [Plan network outbound connectivity for Azure VMs (preview)](site-recovery-azure-to-azure-networking-guidance.md)
### [Plan network infrastructure for on-premises machines](site-recovery-network-design.md)
### [Plan network mapping](site-recovery-network-mapping-azure-to-azure.md)
### [Plan capacity and scale VMware replication to Azure](site-recovery-plan-capacity-vmware.md)
### [Deployment Planner for VMware replication to Azure](site-recovery-deployment-planner.md)
### [Capacity Planner for Hyper-V replication](site-recovery-capacity-planner.md)
### [Control VM replication with role-based access](site-recovery-role-based-linked-access-control.md)

## Configure
### [Set up the source environment](site-recovery-set-up-vmware-to-azure.md)
### [Set up the target environment](site-recovery-prepare-target-vmware-to-azure.md)
### [Configure replication settings](site-recovery-setup-replication-settings-vmware.md)
### [Deploy the Mobility service for VMware replication](site-recovery-vmware-to-azure-install-mob-svc.md)
#### [Deploy the Mobility service with System Center Configuration Manager](site-recovery-install-mobility-service-using-sccm.md)
#### [Deploy the Mobility service with Azure Automation DSC](site-recovery-automate-mobility-service-install.md)
### [Enable replication](site-recovery-replicate-azure-to-azure.md)
## Failover and failback
### [Set up recovery plans](site-recovery-create-recovery-plans.md)
#### [Add Azure runbooks to recovery plans](site-recovery-runbook-automation.md)
### [Run a test failover](site-recovery-test-failover-to-azure.md)
### [Fail over protected machines](site-recovery-failover.md)
### [Reprotect machines after failover](site-recovery-how-to-reprotect-azure-to-azure.md)
### [Fail back from Azure](site-recovery-failback-azure-to-vmware.md)

## Migrate
### [Migrate to Azure](site-recovery-migrate-to-azure.md)
### [Migrate between Azure regions](site-recovery-migrate-azure-to-azure.md)
### [Migrate AWS Windows instances to Azure](site-recovery-migrate-aws-to-azure.md)
### [Replicate migrated machines to another Azure region](site-recovery-azure-to-azure-after-migration.md)

## Workloads
### [Active Directory and DNS](site-recovery-active-directory.md)
### [SQL Server](site-recovery-sql.md)
### [SharePoint](site-recovery-sharepoint.md)
### [Dynamics AX](site-recovery-dynamicsax.md)
### [RDS](site-recovery-workload.md#protect-rds)
### [Exchange](site-recovery-workload.md#protect-exchange)
### [SAP](site-recovery-workload.md#protect-sap)
### [IIS based web applications](site-recovery-iis.md)
### [Citrix XenApp and XenDesktop](site-recovery-citrix-xenapp-and-xendesktop.md)
### [Other workloads](site-recovery-workload.md#workload-summary)
## Automate replication
### [Automate Hyper-V replication to Azure (no VMM)](site-recovery-deploy-with-powershell-resource-manager.md)
### [Automate Hyper-V replication to Azure (with VMM)](site-recovery-vmm-to-azure-powershell-resource-manager.md)
### [Automate Hyper-V replication to a secondary site (with VMM)](site-recovery-vmm-to-vmm-powershell-resource-manager.md)
## Manage
### [Edit replication settings](site-recovery-setup-replication-settings-vmware.md#edit-replication-policy.md)
### [Manage process servers in Azure](site-recovery-vmware-setup-azure-ps-resource-manager.md)
### [Manage the configuration server](site-recovery-vmware-to-azure-manage-configuration-server.md)
### [Manage scaled-out process servers](site-recovery-vmware-to-azure-manage-scaleout-process-server.md)
### [Manage vCenter servers](site-recovery-vmware-to-azure-manage-vCenter.md)
### [Remove servers and disable protection](site-recovery-manage-registration-and-protection.md)
## Troubleshoot
### [Collect logs](site-recovery-monitoring-and-troubleshooting.md)
### [Azure VM replication issues](site-recovery-azure-to-azure-troubleshoot-errors.md)
### [On-premises to Azure replication issues](site-recovery-vmware-to-azure-protection-troubleshoot.md)

# Reference
## [PowerShell](/powershell/module/azurerm.siterecovery)
## [PowerShell classic](/powershell/module/azure/?view=azuresmps-3.7.0)
## [REST](https://msdn.microsoft.com/en-us/library/mt750497)

# Related
## [Azure Automation](/azure/automation/)

# Resources
## [Learning path](https://azure.microsoft.com/documentation/learning-paths/site-recovery/)
## [Forum](https://social.msdn.microsoft.com/Forums/azure/en-US/home?forum=hypervrecovmgr)
## [Blog](http://azure.microsoft.com/blog/tag/azure-site-recovery/)
## [Pricing](https://azure.microsoft.com/pricing/details/site-recovery/)
## [Service updates](https://azure.microsoft.com/updates/?product=site-recovery)
