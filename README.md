# SCCM_Checklist
Checklist of SCCM maintenance tasks

## Daily Tasks
<ol>
<li>Check computer count in All Systems collection.</li>
<li>Check that predefined maintenance tasks that are scheduled to run daily are running successfully.</li>
<li>Check the Configuration Manager database status.</li>
<li>Check Configuration Manager site system inboxes for file backlogs.</li>
<li>Check the operating system event logs from the site systems.</li>
<li>Check the SQL Server error log from the site database computer.</li>
<li>Check Configuration Manager alerts.</li>
<li>Check site server status -- processor, memory, disk space.</li>
<li>Check site systems status in the console: Monitoring\ System Status \ Site Status</li>
<li>Montor software distribution in the console: Monitoring \ Distribution Status \ Content Status and Compliance % column</li>
<li>Monitor client health in the console: Monitoring \ Client Status \ Client Health Dashboard</li>
<li>Check WSUS synchronization status in the console: Monitoring \ Software Update Point Synchronization Status and review errors in WSUSCtrl.log and wsyncmgr.log</li>
<li>Check Automatic Deployment Rules in the console: Software Library \ Software Updates \ Automatic Deployment Rules and review errors in RuleEngine.log</li>
<li>Check deployment Compliance % in the console: Monitoring \ Deployments</li>
<li>Check active & inactive client status.</li>
<li>Check system software update and BitLocker compliance reports.</li>
<li>Check count of non-client systems.</li>
<li>Check audit report for previous day activities.</li>
<li>Check site links if applicable.</li>
<li>Check status filter rules.</li>
<li>Check client scan error counts using report "Troubleshooting 1 - Scan Errors".</li>
</ol>

## Weekly Tasks
<ol>
<li>Target client push to collections of computers without SCCM client and with outdated version of SCCM client.</li>
<li>Review application, security, and system event logs on site servers.</li>
<li>Check the site database size and verify there's enough available disk space on the site database server so that the site database can grow.</li>
<li>Check available disk space on all site systems.</li>
<li>Review collection evaluation.</li>
<li>Verify old computer resource records have been removed.</li>
</ol>

## Monthly Tasks
<ol>
<li>Perform WSUS maintenance tasks: https://learn.microsoft.com/en-US/troubleshoot/mem/configmgr/update-management/wsus-maintenance-guide</li>
<li>Change accounts and passwords, if it's necessary, according to your security plan.</li>
<li>Check network performance to ensure that changes haven't been made that affect site operations.</li>
<li>Check that Active Directory settings that affect site operations haven't changed. For example, check that subnets that are assigned to Active Directory sites and that are used as boundaries for Configuration Manager site haven't changed.</li>
<li>Review configuration baseline compliance using canned report "Summary compliance by configuration baseline".</li>
<li>Review SCCM Clients.</li>
<li>Review SCCM site settings on all SCCM servers.</li>
<li>Performance review.</li>
<li>review number of incremental collections.</li>
<li>Review Management Insights data.</li>
</ol>

## Quarterly Tasks
<ol>
<li>Content library cleanup tool: https://learn.microsoft.com/en-us/mem/configmgr/core/plan-design/hierarchy/content-library-cleanup-tool.</li>
<li>Review the Configuration Manager hierarchy design for any required changes.</li>
<li>Review site certificates to renew any soon expiring.</li>
<li>Review SCCM Site boundaries.</li>
<li>Review SCCM-OU Mapping.</li>
<li>Review Infrastructure related issues.</li>
<li>Capacity planning& further up gradationin current environment.</li>
<li>Review SCCM reports, asset inventory and system compliance including software deployment old software uninstallation.</li>
<li>Review security updates on sccm servers.</li>
<li>SCCM hierarchy review & Envisioning and Architecture Development for new versions.</li>
<li>Check network performance to ensure changes have not been made that affect site operations.</li>
<li>Review SCCM updates & SQL updates for all sccm servers.</li>
<li>Check hardware /virtualization for available updates (drivers, VMWARE tools, VMWAre hardware version).</li>
</ol>

## Bi-Annual Tasks
<ol>
<li>Create/update SCCM operational documents.</li> 
<li>Review SCCM Design for any needed changes.</li>
<li>Review Maintenance plan.</li>
<li>Check network performance to ensure changes have not been made that affect site operations.</li>
<li>Review and delete unnecessary SCCM objects.</li
<li>Review your disaster recovery plan for any required changes.</li>
<li>Do a site recovery according to the disaster recovery plan in a test lab by using a backup copy of the most recent backup that the Backup Site Server maintenance task created.</li>                  
</ol>

## Post-Upgrade Tasks
<ol>
  <li>placeholder</li>
</ol>

## Sources
http://docshare01.docshare.tips/files/23828/238280542.pdf </br>
https://docs.microsoft.com/en-us/mem/configmgr/core/servers/manage/maintenance-tasks </br>
https://www.enhansoft.com/new-years-checklist-for-configuration-manager/ </br>
https://www.systemcenterdudes.com/sccm-daily-maintenance-tasks/
