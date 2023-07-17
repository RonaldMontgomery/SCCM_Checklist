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
<li>Check site server status.</li>
<li>Check site systems status.</li>
<li>Check active & inactive client status.</li>
<li>Check system performance. (IIS connections and performance?)</li>
<li>System compliance reports.</li>
<li>Installation of sccm client on non-client systems.</li>
<li>Check audit report for previous day activities.</li>
<li>Check site links if applicable.</li>
<li>Check status filter rules.</li>
<li>Check client scan error counts using report "Troubleshooting 1 - Scan Errors".</li>
</ol>

## Weekly Tasks
<ol>
<li>Check that predefined maintenance tasks that are scheduled to run weekly are running successfully.</li>
<li>Back up application, security, and system event logs and clear them.</li>
<li>Check the site database size and verify there's enough available disk space on the site database server so that the site database can grow.</li>
<li>Do SQL Server database maintenance on the site database according to your SQL Server maintenance plan.</li>
<li>Check available disk space on all site systems.</li>
<li>Run disk defragmentation tools on all site systems.</li>
<li>Delete unnecessary SCCM objects.</li>
<li>Check system performance issues.</li>
<li>Check advertisement status.</li>
<li>Review Package status.</li>
<li>Review sync between SCCM Primary & Secondary sites.</li>
<li>Clean out old machines and user accounts.</li>
<li>Perform WSUS database maintenance.</li>
</ol>

## Monthly Tasks
<ol>
<li>Change accounts and passwords, if it's necessary, according to your security plan.</li>
<li>Review the maintenance plan to check that scheduled maintenance tasks are scheduled correctly and effectively depending on configured site settings.</li>
<li>Review the Configuration Manager hierarchy design for any required changes.</li>
<li>Check network performance to ensure that changes haven't been made that affect site operations.</li>
<li>Check that Active Directory settings that affect site operations haven't changed. For example, check that subnets that are assigned to Active Directory sites and that are used as boundaries for Configuration Manager site haven't changed.</li>
<li>Review your disaster recovery plan for any required changes.</li>
<li>Do a site recovery according to the disaster recovery plan in a test lab by using a backup copy of the most recent backup that the Backup Site Server maintenance task created.</li>
<li>Check hardware for any errors or for available hardware updates.</li>
<li>Check the overall health of the site.</li>
<li>Monthly Patching for all client systems.</li> 
<li>Review Windows patch compliance.</li>
<li>Review advertisement success/failure rate.</li>
<li>Review configuration baseline compliance using canned report "Summary compliance by configuration baseline".</li>
<li>Review SCCM updates & SQL updates on all sccm servers.</li>
<li>Review SCCM Clients.</li>
<li>Review SCCM site settings on all SCCM servers.</li>
<li>Performance review.</li>
<li>review number of incremental collections.</li>
<li>Review Management Insights data.</li>
</ol>

## Quarterly Tasks
<ol>
<li>Content library cleanup tool.</li>
<li>Review SCCM Site boundaries.</li>
<li>Review SCCM-OU Mapping.</li>
<li>Review Infrastructure related issues.</li>
<li>Capacity planning& further up gradationin current environment.</li>
<li>Review SCCM reports, asset inventory and system compliance including software deployment old software uninstallation.</li>
<li>Review security updates on sccm servers.</li>
<li>SCCM hierarchy review & Envisioning and Architecture Development for new versions.</li>
<li>Check network performance to ensure changes have not been made that affect site operations.</li>
</ol>

## Bi-Annual Tasks
<ol>
<li>Create/update SCCM operational documents.</li> 
<li>Review SCCM Design.</li>
<li>Review Maintenance plan.</li>
<li>Review the hierarchy design for any needed changes.</li>
<li>Check overall health of site.</li>
<li>Check network performance to ensure changes have not been made that affect site operations.</li>
</ol>

## Post-Upgrade Tasks
<ol>
  <li>placeholder</li>
</ol>

## Sources
http://docshare01.docshare.tips/files/23828/238280542.pdf </br>
https://docs.microsoft.com/en-us/mem/configmgr/core/servers/manage/maintenance-tasks </br>
https://www.enhansoft.com/new-years-checklist-for-configuration-manager/ </br>
