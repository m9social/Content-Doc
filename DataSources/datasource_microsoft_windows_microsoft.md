Vendor: Microsoft
=================
Product: Microsoft Windows
--------------------------

### Use Cases

_The following Use Cases can be operationalized using log data from this data source_

* [Account Creation and Management](../UseCases/usecase_account_creation_and_management.md)
* [Activity Time  and Type](../UseCases/usecase_activity_time__and_type.md)
* [Application Activity](../UseCases/usecase_application_activity.md)
* [Asset Activity Monitoring](../UseCases/usecase_asset_activity_monitoring.md)
* [Asset Logon and Access](../UseCases/usecase_asset_logon_and_access.md)
* [Badge Access](../UseCases/usecase_badge_access.md)
* [Credential Switch Activity](../UseCases/usecase_credential_switch_activity.md)
* [Critical System Activity](../UseCases/usecase_critical_system_activity.md)
* [Data Loss Prevention](../UseCases/usecase_data_loss_prevention.md)
* [Email Activity](../UseCases/usecase_email_activity.md)
* [Endpoint Activity](../UseCases/usecase_endpoint_activity.md)
* [Executives](../UseCases/usecase_executives.md)
* [Failed Logon and Account Lockout](../UseCases/usecase_failed_logon_and_account_lockout.md)
* [File Activity](../UseCases/usecase_file_activity.md)
* [Network](../UseCases/usecase_network.md)
* [Network zones and Location Access](../UseCases/usecase_network_zones_and_location_access.md)
* [Pass The Hash and Golden Ticket](../UseCases/usecase_pass_the_hash_and_golden_ticket.md)
* [Privileged Activity](../UseCases/usecase_privileged_activity.md)
* [Security Alert](../UseCases/usecase_security_alert.md)
* [Security Operations](../UseCases/usecase_security_operations.md)
* [Service Account Activity](../UseCases/usecase_service_account_activity.md)
* [Web Activity](../UseCases/usecase_web_activity.md)


### Event Types

_The following list of Event Types can be generated by Data Source Microsoft Windows_Microsoft, and power the use cases above:_

- dns-response
- account-disabled
- task-created
- share-access-denied
- authentication-failed
- service-logon
- account-creation
- dns-query
- file-read
- member-added
- account-password-change
- nac-logon
- process-created
- privileged-access
- ntlm-logon
- privileged-object-access
- workstation-unlocked
- network-connection-successful
- account-password-reset
- app-login
- failed-logon
- service-created
- process-network-failed
- audit-log-clear
- workstation-locked
- batch-logon
- member-removed
- audit-policy-change
- usb-insert
- account-deleted
- remote-logon
- winsession-disconnect
- kerberos-logon
- file-delete
- account-switch
- account-lockout
- computer-logon
- failed-app-login
- ds-access
- process-network
- account-unlocked
- share-access
- remote-access
- local-logon
- security-alert
- nac-failed-logon
- account-enabled
- account-password-change-failed
- file-write


### Parsers

_The following Parsers can be operationalized using log data from this data source_

* [azure-app-logon](../Parsers/parserContent_azure-app-logon.md)
* [azure-app-logon-2](../Parsers/parserContent_azure-app-logon-2.md)
* [cef-4624](../Parsers/parserContent_cef-4624.md)
* [cef-4625](../Parsers/parserContent_cef-4625.md)
* [cef-4648](../Parsers/parserContent_cef-4648.md)
* [cef-4663](../Parsers/parserContent_cef-4663.md)
* [cef-4672](../Parsers/parserContent_cef-4672.md)
* [cef-4673](../Parsers/parserContent_cef-4673.md)
* [cef-4674](../Parsers/parserContent_cef-4674.md)
* [cef-4688](../Parsers/parserContent_cef-4688.md)
* [cef-4720](../Parsers/parserContent_cef-4720.md)
* [cef-4722](../Parsers/parserContent_cef-4722.md)
* [cef-4723](../Parsers/parserContent_cef-4723.md)
* [cef-4724](../Parsers/parserContent_cef-4724.md)
* [cef-4725](../Parsers/parserContent_cef-4725.md)
* [cef-4740](../Parsers/parserContent_cef-4740.md)
* [cef-4768](../Parsers/parserContent_cef-4768.md)
* [cef-4769](../Parsers/parserContent_cef-4769.md)
* [cef-4771](../Parsers/parserContent_cef-4771.md)
* [cef-4776](../Parsers/parserContent_cef-4776.md)
* [cef-4800](../Parsers/parserContent_cef-4800.md)
* [cef-4801](../Parsers/parserContent_cef-4801.md)
* [cef-5145](../Parsers/parserContent_cef-5145.md)
* [cef-528](../Parsers/parserContent_cef-528.md)
* [cef-540](../Parsers/parserContent_cef-540.md)
* [cef-576](../Parsers/parserContent_cef-576.md)
* [cef-624](../Parsers/parserContent_cef-624.md)
* [cef-672](../Parsers/parserContent_cef-672.md)
* [cef-673](../Parsers/parserContent_cef-673.md)
* [cef-azure-process-created](../Parsers/parserContent_cef-azure-process-created.md)
* [cef-member-added-2003](../Parsers/parserContent_cef-member-added-2003.md)
* [cef-member-added-2008](../Parsers/parserContent_cef-member-added-2008.md)
* [cef-member-removed-2008](../Parsers/parserContent_cef-member-removed-2008.md)
* [cef-powershell-300](../Parsers/parserContent_cef-powershell-300.md)
* [cef-powershell-4102](../Parsers/parserContent_cef-powershell-4102.md)
* [cef-powershell-4104](../Parsers/parserContent_cef-powershell-4104.md)
* [cef-powershell-600](../Parsers/parserContent_cef-powershell-600.md)
* [cef-snare-4624](../Parsers/parserContent_cef-snare-4624.md)
* [cef-snare-4648](../Parsers/parserContent_cef-snare-4648.md)
* [cef-snare-4663](../Parsers/parserContent_cef-snare-4663.md)
* [cef-snare-4673](../Parsers/parserContent_cef-snare-4673.md)
* [cef-snare-4688](../Parsers/parserContent_cef-snare-4688.md)
* [cef-snare-4719](../Parsers/parserContent_cef-snare-4719.md)
* [cef-snare-4769](../Parsers/parserContent_cef-snare-4769.md)
* [cef-snare-5136](../Parsers/parserContent_cef-snare-5136.md)
* [cef-snare-552](../Parsers/parserContent_cef-snare-552.md)
* [cef-snare-567](../Parsers/parserContent_cef-snare-567.md)
* [cef-snare-576](../Parsers/parserContent_cef-snare-576.md)
* [cef-snare-577](../Parsers/parserContent_cef-snare-577.md)
* [cef-snare-578](../Parsers/parserContent_cef-snare-578.md)
* [cef-snare-680](../Parsers/parserContent_cef-snare-680.md)
* [cef-snare-process-created](../Parsers/parserContent_cef-snare-process-created.md)
* [cef-windows-4104](../Parsers/parserContent_cef-windows-4104.md)
* [cef-windows-4624](../Parsers/parserContent_cef-windows-4624.md)
* [cef-windows-4625](../Parsers/parserContent_cef-windows-4625.md)
* [cef-windows-4673](../Parsers/parserContent_cef-windows-4673.md)
* [cef-windows-4674](../Parsers/parserContent_cef-windows-4674.md)
* [cef-windows-4742](../Parsers/parserContent_cef-windows-4742.md)
* [cef-windows-4768](../Parsers/parserContent_cef-windows-4768.md)
* [cef-windows-4769](../Parsers/parserContent_cef-windows-4769.md)
* [cef-windows-4771](../Parsers/parserContent_cef-windows-4771.md)
* [cef-windows-4776](../Parsers/parserContent_cef-windows-4776.md)
* [cef-windows-6416](../Parsers/parserContent_cef-windows-6416.md)
* [cef-windows-dns-query](../Parsers/parserContent_cef-windows-dns-query.md)
* [cef-windows-dns-query-1](../Parsers/parserContent_cef-windows-dns-query-1.md)
* [cef-windows-member-added-2003](../Parsers/parserContent_cef-windows-member-added-2003.md)
* [cef-windows-member-removed-2003](../Parsers/parserContent_cef-windows-member-removed-2003.md)
* [emc-syslog-4624](../Parsers/parserContent_emc-syslog-4624.md)
* [emc-syslog-4625](../Parsers/parserContent_emc-syslog-4625.md)
* [emc-syslog-4648](../Parsers/parserContent_emc-syslog-4648.md)
* [emc-syslog-4672](../Parsers/parserContent_emc-syslog-4672.md)
* [emc-syslog-4673](../Parsers/parserContent_emc-syslog-4673.md)
* [emc-syslog-4674](../Parsers/parserContent_emc-syslog-4674.md)
* [emc-syslog-4688](../Parsers/parserContent_emc-syslog-4688.md)
* [emc-syslog-4723](../Parsers/parserContent_emc-syslog-4723.md)
* [emc-syslog-4740](../Parsers/parserContent_emc-syslog-4740.md)
* [emc-syslog-4768](../Parsers/parserContent_emc-syslog-4768.md)
* [emc-syslog-4769](../Parsers/parserContent_emc-syslog-4769.md)
* [emc-syslog-4776](../Parsers/parserContent_emc-syslog-4776.md)
* [emc-syslog-member-added-2008](../Parsers/parserContent_emc-syslog-member-added-2008.md)
* [evntslog-528](../Parsers/parserContent_evntslog-528.md)
* [evntslog-672](../Parsers/parserContent_evntslog-672.md)
* [evntslog-673](../Parsers/parserContent_evntslog-673.md)
* [evntslog-675](../Parsers/parserContent_evntslog-675.md)
* [evntslog-680](../Parsers/parserContent_evntslog-680.md)
* [evntslog-member-added-2003](../Parsers/parserContent_evntslog-member-added-2003.md)
* [exalms-4625](../Parsers/parserContent_exalms-4625.md)
* [exalms-4662](../Parsers/parserContent_exalms-4662.md)
* [exalms-4663](../Parsers/parserContent_exalms-4663.md)
* [exalms-4674](../Parsers/parserContent_exalms-4674.md)
* [exalms-4719](../Parsers/parserContent_exalms-4719.md)
* [exalms-4742](../Parsers/parserContent_exalms-4742.md)
* [exalms-4776](../Parsers/parserContent_exalms-4776.md)
* [exalms-540](../Parsers/parserContent_exalms-540.md)
* [exalms-552](../Parsers/parserContent_exalms-552.md)
* [exalms-567](../Parsers/parserContent_exalms-567.md)
* [exalms-576](../Parsers/parserContent_exalms-576.md)
* [exalms-680](../Parsers/parserContent_exalms-680.md)
* [extrahop-4768](../Parsers/parserContent_extrahop-4768.md)
* [extrahop-4769](../Parsers/parserContent_extrahop-4769.md)
* [extrahop-4771](../Parsers/parserContent_extrahop-4771.md)
* [greenbay-4776](../Parsers/parserContent_greenbay-4776.md)
* [greenbay-privileged-access](../Parsers/parserContent_greenbay-privileged-access.md)
* [json-4624](../Parsers/parserContent_json-4624.md)
* [json-4625](../Parsers/parserContent_json-4625.md)
* [json-4648](../Parsers/parserContent_json-4648.md)
* [json-4674](../Parsers/parserContent_json-4674.md)
* [json-4720](../Parsers/parserContent_json-4720.md)
* [json-4724](../Parsers/parserContent_json-4724.md)
* [json-4740](../Parsers/parserContent_json-4740.md)
* [json-4768](../Parsers/parserContent_json-4768.md)
* [json-4769](../Parsers/parserContent_json-4769.md)
* [json-4771](../Parsers/parserContent_json-4771.md)
* [json-4776](../Parsers/parserContent_json-4776.md)
* [json-4779](../Parsers/parserContent_json-4779.md)
* [json-4800](../Parsers/parserContent_json-4800.md)
* [json-5145](../Parsers/parserContent_json-5145.md)
* [json-member-added-2008](../Parsers/parserContent_json-member-added-2008.md)
* [json-process-created](../Parsers/parserContent_json-process-created.md)
* [json-process-created-1](../Parsers/parserContent_json-process-created-1.md)
* [json-process-created-2](../Parsers/parserContent_json-process-created-2.md)
* [json-windows-dns-query](../Parsers/parserContent_json-windows-dns-query.md)
* [json-windows-dns-response](../Parsers/parserContent_json-windows-dns-response.md)
* [json-windows-events-netlogon](../Parsers/parserContent_json-windows-events-netlogon.md)
* [json-xml-4673](../Parsers/parserContent_json-xml-4673.md)
* [json-xml-4768](../Parsers/parserContent_json-xml-4768.md)
* [json-xml-4769](../Parsers/parserContent_json-xml-4769.md)
* [json-xml-4771](../Parsers/parserContent_json-xml-4771.md)
* [json-xml-5156](../Parsers/parserContent_json-xml-5156.md)
* [json-xml-5157](../Parsers/parserContent_json-xml-5157.md)
* [json-xml-5158](../Parsers/parserContent_json-xml-5158.md)
* [l-4672](../Parsers/parserContent_l-4672.md)
* [l-4673](../Parsers/parserContent_l-4673.md)
* [l-4674](../Parsers/parserContent_l-4674.md)
* [l-4688-v2](../Parsers/parserContent_l-4688-v2.md)
* [l-4720](../Parsers/parserContent_l-4720.md)
* [l-4722](../Parsers/parserContent_l-4722.md)
* [l-4723](../Parsers/parserContent_l-4723.md)
* [l-4724](../Parsers/parserContent_l-4724.md)
* [l-4725](../Parsers/parserContent_l-4725.md)
* [l-4740](../Parsers/parserContent_l-4740.md)
* [l-4767](../Parsers/parserContent_l-4767.md)
* [l-member-added-2008](../Parsers/parserContent_l-member-added-2008.md)
* [logstash-4624](../Parsers/parserContent_logstash-4624.md)
* [logstash-4768](../Parsers/parserContent_logstash-4768.md)
* [logstash-4769](../Parsers/parserContent_logstash-4769.md)
* [mcafee-siem-4624](../Parsers/parserContent_mcafee-siem-4624.md)
* [mcafee-siem-4625](../Parsers/parserContent_mcafee-siem-4625.md)
* [mcafee-siem-4648](../Parsers/parserContent_mcafee-siem-4648.md)
* [mcafee-siem-4672](../Parsers/parserContent_mcafee-siem-4672.md)
* [mcafee-siem-4720](../Parsers/parserContent_mcafee-siem-4720.md)
* [mcafee-siem-4722](../Parsers/parserContent_mcafee-siem-4722.md)
* [mcafee-siem-4723](../Parsers/parserContent_mcafee-siem-4723.md)
* [mcafee-siem-4724](../Parsers/parserContent_mcafee-siem-4724.md)
* [mcafee-siem-4725](../Parsers/parserContent_mcafee-siem-4725.md)
* [mcafee-siem-4726](../Parsers/parserContent_mcafee-siem-4726.md)
* [mcafee-siem-4740](../Parsers/parserContent_mcafee-siem-4740.md)
* [mcafee-siem-4768](../Parsers/parserContent_mcafee-siem-4768.md)
* [mcafee-siem-4769](../Parsers/parserContent_mcafee-siem-4769.md)
* [mcafee-siem-4771](../Parsers/parserContent_mcafee-siem-4771.md)
* [mcafee-siem-4776](../Parsers/parserContent_mcafee-siem-4776.md)
* [mcafee-siem-4778](../Parsers/parserContent_mcafee-siem-4778.md)
* [mcafee-siem-4779](../Parsers/parserContent_mcafee-siem-4779.md)
* [mcafee-siem-5136](../Parsers/parserContent_mcafee-siem-5136.md)
* [mcafee-siem-5137](../Parsers/parserContent_mcafee-siem-5137.md)
* [mcafee-siem-5141](../Parsers/parserContent_mcafee-siem-5141.md)
* [mcafee-siem-process-created](../Parsers/parserContent_mcafee-siem-process-created.md)
* [metricbeat-5156](../Parsers/parserContent_metricbeat-5156.md)
* [microsoft-dns-renew-jp](../Parsers/parserContent_microsoft-dns-renew-jp.md)
* [n-forwarded-cef-4624](../Parsers/parserContent_n-forwarded-cef-4624.md)
* [n-forwarded-cef-4625](../Parsers/parserContent_n-forwarded-cef-4625.md)
* [n-forwarded-cef-4648](../Parsers/parserContent_n-forwarded-cef-4648.md)
* [n-forwarded-cef-4662](../Parsers/parserContent_n-forwarded-cef-4662.md)
* [n-forwarded-cef-4663](../Parsers/parserContent_n-forwarded-cef-4663.md)
* [n-forwarded-cef-4672](../Parsers/parserContent_n-forwarded-cef-4672.md)
* [n-forwarded-cef-4673](../Parsers/parserContent_n-forwarded-cef-4673.md)
* [n-forwarded-cef-4688](../Parsers/parserContent_n-forwarded-cef-4688.md)
* [n-forwarded-cef-4722](../Parsers/parserContent_n-forwarded-cef-4722.md)
* [n-forwarded-cef-4724](../Parsers/parserContent_n-forwarded-cef-4724.md)
* [n-forwarded-cef-4725](../Parsers/parserContent_n-forwarded-cef-4725.md)
* [n-forwarded-cef-4740](../Parsers/parserContent_n-forwarded-cef-4740.md)
* [n-forwarded-cef-4768](../Parsers/parserContent_n-forwarded-cef-4768.md)
* [n-forwarded-cef-4769](../Parsers/parserContent_n-forwarded-cef-4769.md)
* [n-forwarded-cef-4771](../Parsers/parserContent_n-forwarded-cef-4771.md)
* [n-forwarded-cef-4776](../Parsers/parserContent_n-forwarded-cef-4776.md)
* [n-forwarded-cef-5136](../Parsers/parserContent_n-forwarded-cef-5136.md)
* [n-forwarded-cef-528](../Parsers/parserContent_n-forwarded-cef-528.md)
* [n-forwarded-cef-540](../Parsers/parserContent_n-forwarded-cef-540.md)
* [n-forwarded-cef-552](../Parsers/parserContent_n-forwarded-cef-552.md)
* [n-forwarded-cef-680](../Parsers/parserContent_n-forwarded-cef-680.md)
* [n-forwarded-cef-dns-update](../Parsers/parserContent_n-forwarded-cef-dns-update.md)
* [n-forwarded-cef-failed-logon-2003](../Parsers/parserContent_n-forwarded-cef-failed-logon-2003.md)
* [n-forwarded-cef-member-added-2008](../Parsers/parserContent_n-forwarded-cef-member-added-2008.md)
* [n-forwarded-cef-member-removed-2008](../Parsers/parserContent_n-forwarded-cef-member-removed-2008.md)
* [nic-4688](../Parsers/parserContent_nic-4688.md)
* [nic-5136](../Parsers/parserContent_nic-5136.md)
* [nic-5137](../Parsers/parserContent_nic-5137.md)
* [nic-5141](../Parsers/parserContent_nic-5141.md)
* [nic-528](../Parsers/parserContent_nic-528.md)
* [nic-627](../Parsers/parserContent_nic-627.md)
* [nic-member-removed-2003](../Parsers/parserContent_nic-member-removed-2003.md)
* [nic-member-removed-2008](../Parsers/parserContent_nic-member-removed-2008.md)
* [powershell-4104](../Parsers/parserContent_powershell-4104.md)
* [powershell-800](../Parsers/parserContent_powershell-800.md)
* [powershell-800-syslog](../Parsers/parserContent_powershell-800-syslog.md)
* [powershell-process-created](../Parsers/parserContent_powershell-process-created.md)
* [powershell-process-created-1](../Parsers/parserContent_powershell-process-created-1.md)
* [powershell-process-created-2](../Parsers/parserContent_powershell-process-created-2.md)
* [q-4662](../Parsers/parserContent_q-4662.md)
* [q-4697](../Parsers/parserContent_q-4697.md)
* [q-4698](../Parsers/parserContent_q-4698.md)
* [q-4800](../Parsers/parserContent_q-4800.md)
* [q-4801](../Parsers/parserContent_q-4801.md)
* [q-5156](../Parsers/parserContent_q-5156.md)
* [q-5158](../Parsers/parserContent_q-5158.md)
* [q-6272](../Parsers/parserContent_q-6272.md)
* [q-6273](../Parsers/parserContent_q-6273.md)
* [q-628](../Parsers/parserContent_q-628.md)
* [q-672](../Parsers/parserContent_q-672.md)
* [q-673](../Parsers/parserContent_q-673.md)
* [q-675](../Parsers/parserContent_q-675.md)
* [q-680](../Parsers/parserContent_q-680.md)
* [q-member-added-2008](../Parsers/parserContent_q-member-added-2008.md)
* [q-member-removed-2003](../Parsers/parserContent_q-member-removed-2003.md)
* [q-member-removed-2008](../Parsers/parserContent_q-member-removed-2008.md)
* [q-microsoft-4648](../Parsers/parserContent_q-microsoft-4648.md)
* [q-microsoft-4719](../Parsers/parserContent_q-microsoft-4719.md)
* [q-microsoft-4740](../Parsers/parserContent_q-microsoft-4740.md)
* [q-microsoft-dhcp](../Parsers/parserContent_q-microsoft-dhcp.md)
* [q-microsoft-dhcp-renew](../Parsers/parserContent_q-microsoft-dhcp-renew.md)
* [q-microsoft-dhcp-update](../Parsers/parserContent_q-microsoft-dhcp-update.md)
* [r-nic-4771](../Parsers/parserContent_r-nic-4771.md)
* [r-nic-528](../Parsers/parserContent_r-nic-528.md)
* [r-nic-540](../Parsers/parserContent_r-nic-540.md)
* [r-syslog-5136](../Parsers/parserContent_r-syslog-5136.md)
* [raw-104](../Parsers/parserContent_raw-104.md)
* [raw-1102](../Parsers/parserContent_raw-1102.md)
* [raw-4104](../Parsers/parserContent_raw-4104.md)
* [raw-4624](../Parsers/parserContent_raw-4624.md)
* [raw-4624-1](../Parsers/parserContent_raw-4624-1.md)
* [raw-4624-2](../Parsers/parserContent_raw-4624-2.md)
* [raw-4624-3](../Parsers/parserContent_raw-4624-3.md)
* [raw-4624-4](../Parsers/parserContent_raw-4624-4.md)
* [raw-4624-5](../Parsers/parserContent_raw-4624-5.md)
* [raw-4624-6](../Parsers/parserContent_raw-4624-6.md)
* [raw-4624-7](../Parsers/parserContent_raw-4624-7.md)
* [raw-4624-8](../Parsers/parserContent_raw-4624-8.md)
* [raw-4624-9](../Parsers/parserContent_raw-4624-9.md)
* [raw-4625](../Parsers/parserContent_raw-4625.md)
* [raw-4625-1](../Parsers/parserContent_raw-4625-1.md)
* [raw-4648](../Parsers/parserContent_raw-4648.md)
* [raw-4648-1](../Parsers/parserContent_raw-4648-1.md)
* [raw-4648-2](../Parsers/parserContent_raw-4648-2.md)
* [raw-4648-3](../Parsers/parserContent_raw-4648-3.md)
* [raw-4648-4](../Parsers/parserContent_raw-4648-4.md)
* [raw-4662](../Parsers/parserContent_raw-4662.md)
* [raw-4662-1](../Parsers/parserContent_raw-4662-1.md)
* [raw-4663](../Parsers/parserContent_raw-4663.md)
* [raw-4663-1](../Parsers/parserContent_raw-4663-1.md)
* [raw-4663-10](../Parsers/parserContent_raw-4663-10.md)
* [raw-4663-2](../Parsers/parserContent_raw-4663-2.md)
* [raw-4663-3](../Parsers/parserContent_raw-4663-3.md)
* [raw-4663-4](../Parsers/parserContent_raw-4663-4.md)
* [raw-4663-5](../Parsers/parserContent_raw-4663-5.md)
* [raw-4663-6](../Parsers/parserContent_raw-4663-6.md)
* [raw-4663-7](../Parsers/parserContent_raw-4663-7.md)
* [raw-4663-8](../Parsers/parserContent_raw-4663-8.md)
* [raw-4663-9](../Parsers/parserContent_raw-4663-9.md)
* [raw-4672](../Parsers/parserContent_raw-4672.md)
* [raw-4672-1](../Parsers/parserContent_raw-4672-1.md)
* [raw-4673](../Parsers/parserContent_raw-4673.md)
* [raw-4674](../Parsers/parserContent_raw-4674.md)
* [raw-4674-1](../Parsers/parserContent_raw-4674-1.md)
* [raw-4674-2](../Parsers/parserContent_raw-4674-2.md)
* [raw-4674-3](../Parsers/parserContent_raw-4674-3.md)
* [raw-4700](../Parsers/parserContent_raw-4700.md)
* [raw-4719](../Parsers/parserContent_raw-4719.md)
* [raw-4723](../Parsers/parserContent_raw-4723.md)
* [raw-4724](../Parsers/parserContent_raw-4724.md)
* [raw-4738](../Parsers/parserContent_raw-4738.md)
* [raw-4742](../Parsers/parserContent_raw-4742.md)
* [raw-4767](../Parsers/parserContent_raw-4767.md)
* [raw-4768](../Parsers/parserContent_raw-4768.md)
* [raw-4768-1](../Parsers/parserContent_raw-4768-1.md)
* [raw-4768-2](../Parsers/parserContent_raw-4768-2.md)
* [raw-4768-3](../Parsers/parserContent_raw-4768-3.md)
* [raw-4768-4](../Parsers/parserContent_raw-4768-4.md)
* [raw-4769](../Parsers/parserContent_raw-4769.md)
* [raw-4769-1](../Parsers/parserContent_raw-4769-1.md)
* [raw-4769-2](../Parsers/parserContent_raw-4769-2.md)
* [raw-4769-3](../Parsers/parserContent_raw-4769-3.md)
* [raw-4769-4](../Parsers/parserContent_raw-4769-4.md)
* [raw-4769-5](../Parsers/parserContent_raw-4769-5.md)
* [raw-4769-6](../Parsers/parserContent_raw-4769-6.md)
* [raw-4771](../Parsers/parserContent_raw-4771.md)
* [raw-4776](../Parsers/parserContent_raw-4776.md)
* [raw-4776-1](../Parsers/parserContent_raw-4776-1.md)
* [raw-4776-2](../Parsers/parserContent_raw-4776-2.md)
* [raw-4776-3](../Parsers/parserContent_raw-4776-3.md)
* [raw-4776-4](../Parsers/parserContent_raw-4776-4.md)
* [raw-4778](../Parsers/parserContent_raw-4778.md)
* [raw-4778-1](../Parsers/parserContent_raw-4778-1.md)
* [raw-4779](../Parsers/parserContent_raw-4779.md)
* [raw-4800](../Parsers/parserContent_raw-4800.md)
* [raw-4801](../Parsers/parserContent_raw-4801.md)
* [raw-5136](../Parsers/parserContent_raw-5136.md)
* [raw-5137](../Parsers/parserContent_raw-5137.md)
* [raw-5141](../Parsers/parserContent_raw-5141.md)
* [raw-5145](../Parsers/parserContent_raw-5145.md)
* [raw-5145-1](../Parsers/parserContent_raw-5145-1.md)
* [raw-5145-2](../Parsers/parserContent_raw-5145-2.md)
* [raw-5145-3](../Parsers/parserContent_raw-5145-3.md)
* [raw-5145-4](../Parsers/parserContent_raw-5145-4.md)
* [raw-5145-5](../Parsers/parserContent_raw-5145-5.md)
* [raw-5145-6](../Parsers/parserContent_raw-5145-6.md)
* [raw-5145-7](../Parsers/parserContent_raw-5145-7.md)
* [raw-5145-8](../Parsers/parserContent_raw-5145-8.md)
* [raw-5145-9](../Parsers/parserContent_raw-5145-9.md)
* [raw-5156](../Parsers/parserContent_raw-5156.md)
* [raw-5157](../Parsers/parserContent_raw-5157.md)
* [raw-528](../Parsers/parserContent_raw-528.md)
* [raw-540](../Parsers/parserContent_raw-540.md)
* [raw-552](../Parsers/parserContent_raw-552.md)
* [raw-567](../Parsers/parserContent_raw-567.md)
* [raw-627](../Parsers/parserContent_raw-627.md)
* [raw-628](../Parsers/parserContent_raw-628.md)
* [raw-672](../Parsers/parserContent_raw-672.md)
* [raw-673](../Parsers/parserContent_raw-673.md)
* [raw-675](../Parsers/parserContent_raw-675.md)
* [raw-680](../Parsers/parserContent_raw-680.md)
* [raw-7045](../Parsers/parserContent_raw-7045.md)
* [raw-8004-1](../Parsers/parserContent_raw-8004-1.md)
* [raw-failed-logon-2003](../Parsers/parserContent_raw-failed-logon-2003.md)
* [raw-member-added-2003](../Parsers/parserContent_raw-member-added-2003.md)
* [raw-member-added-2008](../Parsers/parserContent_raw-member-added-2008.md)
* [raw-member-removed-2003](../Parsers/parserContent_raw-member-removed-2003.md)
* [raw-member-removed-2008](../Parsers/parserContent_raw-member-removed-2008.md)
* [raw-member-removed-2008-1](../Parsers/parserContent_raw-member-removed-2008-1.md)
* [raw-member-removed-2008-2](../Parsers/parserContent_raw-member-removed-2008-2.md)
* [raw-member-removed-2008-3](../Parsers/parserContent_raw-member-removed-2008-3.md)
* [raw-process-created](../Parsers/parserContent_raw-process-created.md)
* [raw-windows-account-4720](../Parsers/parserContent_raw-windows-account-4720.md)
* [raw-windows-account-4722](../Parsers/parserContent_raw-windows-account-4722.md)
* [raw-windows-account-4725](../Parsers/parserContent_raw-windows-account-4725.md)
* [raw-windows-account-4726](../Parsers/parserContent_raw-windows-account-4726.md)
* [raw-windows-account-4740](../Parsers/parserContent_raw-windows-account-4740.md)
* [raw-windows-account-624](../Parsers/parserContent_raw-windows-account-624.md)
* [raw-windows-account-629](../Parsers/parserContent_raw-windows-account-629.md)
* [raw-windows-account-630](../Parsers/parserContent_raw-windows-account-630.md)
* [raw-windows-account-644](../Parsers/parserContent_raw-windows-account-644.md)
* [rs-4624](../Parsers/parserContent_rs-4624.md)
* [rs-4625](../Parsers/parserContent_rs-4625.md)
* [s-4624-jp](../Parsers/parserContent_s-4624-jp.md)
* [s-4625-jp](../Parsers/parserContent_s-4625-jp.md)
* [s-4648-jp](../Parsers/parserContent_s-4648-jp.md)
* [s-4662](../Parsers/parserContent_s-4662.md)
* [s-4663-jp](../Parsers/parserContent_s-4663-jp.md)
* [s-4672-jp](../Parsers/parserContent_s-4672-jp.md)
* [s-4674-jp](../Parsers/parserContent_s-4674-jp.md)
* [s-4688-jp](../Parsers/parserContent_s-4688-jp.md)
* [s-4697](../Parsers/parserContent_s-4697.md)
* [s-4698](../Parsers/parserContent_s-4698.md)
* [s-4719](../Parsers/parserContent_s-4719.md)
* [s-4719-1](../Parsers/parserContent_s-4719-1.md)
* [s-4720-jp](../Parsers/parserContent_s-4720-jp.md)
* [s-4722-jp](../Parsers/parserContent_s-4722-jp.md)
* [s-4723-jp](../Parsers/parserContent_s-4723-jp.md)
* [s-4724-jp](../Parsers/parserContent_s-4724-jp.md)
* [s-4725-jp](../Parsers/parserContent_s-4725-jp.md)
* [s-4726-jp](../Parsers/parserContent_s-4726-jp.md)
* [s-4740-1](../Parsers/parserContent_s-4740-1.md)
* [s-4740-2](../Parsers/parserContent_s-4740-2.md)
* [s-4740-jp](../Parsers/parserContent_s-4740-jp.md)
* [s-4768-jp](../Parsers/parserContent_s-4768-jp.md)
* [s-4769-jp](../Parsers/parserContent_s-4769-jp.md)
* [s-4771-jp](../Parsers/parserContent_s-4771-jp.md)
* [s-4776-jp](../Parsers/parserContent_s-4776-jp.md)
* [s-4801-1](../Parsers/parserContent_s-4801-1.md)
* [s-5137](../Parsers/parserContent_s-5137.md)
* [s-5141](../Parsers/parserContent_s-5141.md)
* [s-5141-1](../Parsers/parserContent_s-5141-1.md)
* [s-517](../Parsers/parserContent_s-517.md)
* [s-560-jp](../Parsers/parserContent_s-560-jp.md)
* [s-576](../Parsers/parserContent_s-576.md)
* [s-592](../Parsers/parserContent_s-592.md)
* [s-612](../Parsers/parserContent_s-612.md)
* [s-680](../Parsers/parserContent_s-680.md)
* [s-7045](../Parsers/parserContent_s-7045.md)
* [s-adfs-auth-failed](../Parsers/parserContent_s-adfs-auth-failed.md)
* [s-json-4697](../Parsers/parserContent_s-json-4697.md)
* [s-member-added-2003](../Parsers/parserContent_s-member-added-2003.md)
* [s-member-added-2008](../Parsers/parserContent_s-member-added-2008.md)
* [s-member-added-2008-jp](../Parsers/parserContent_s-member-added-2008-jp.md)
* [s-member-removed-2003](../Parsers/parserContent_s-member-removed-2003.md)
* [s-member-removed-2008](../Parsers/parserContent_s-member-removed-2008.md)
* [s-microsoft-dhcp](../Parsers/parserContent_s-microsoft-dhcp.md)
* [s-microsoft-dns-renew](../Parsers/parserContent_s-microsoft-dns-renew.md)
* [s-microsoft-dns-update](../Parsers/parserContent_s-microsoft-dns-update.md)
* [s-windows-4625](../Parsers/parserContent_s-windows-4625.md)
* [s-windows-4648](../Parsers/parserContent_s-windows-4648.md)
* [s-windows-4672](../Parsers/parserContent_s-windows-4672.md)
* [s-windows-4673](../Parsers/parserContent_s-windows-4673.md)
* [s-windows-4674](../Parsers/parserContent_s-windows-4674.md)
* [s-windows-4688](../Parsers/parserContent_s-windows-4688.md)
* [s-windows-4771](../Parsers/parserContent_s-windows-4771.md)
* [s-windows-4776](../Parsers/parserContent_s-windows-4776.md)
* [s-windows-5157](../Parsers/parserContent_s-windows-5157.md)
* [s-windows-5157-2](../Parsers/parserContent_s-windows-5157-2.md)
* [s-windows-process-created](../Parsers/parserContent_s-windows-process-created.md)
* [s-xml-4663](../Parsers/parserContent_s-xml-4663.md)
* [s-xml-4697](../Parsers/parserContent_s-xml-4697.md)
* [s-xml-4698](../Parsers/parserContent_s-xml-4698.md)
* [s-xml-4720](../Parsers/parserContent_s-xml-4720.md)
* [s-xml-4723](../Parsers/parserContent_s-xml-4723.md)
* [s-xml-4724](../Parsers/parserContent_s-xml-4724.md)
* [s-xml-4725](../Parsers/parserContent_s-xml-4725.md)
* [s-xml-4726](../Parsers/parserContent_s-xml-4726.md)
* [s-xml-4740](../Parsers/parserContent_s-xml-4740.md)
* [s-xml-4771](../Parsers/parserContent_s-xml-4771.md)
* [s-xml-7045](../Parsers/parserContent_s-xml-7045.md)
* [snare-4719](../Parsers/parserContent_snare-4719.md)
* [snare-517](../Parsers/parserContent_snare-517.md)
* [snare-576](../Parsers/parserContent_snare-576.md)
* [snare-577](../Parsers/parserContent_snare-577.md)
* [snare-578](../Parsers/parserContent_snare-578.md)
* [snare-592](../Parsers/parserContent_snare-592.md)
* [snare-612](../Parsers/parserContent_snare-612.md)
* [snare-cef-member-added-2008](../Parsers/parserContent_snare-cef-member-added-2008.md)
* [syslog-4625-ch](../Parsers/parserContent_syslog-4625-ch.md)
* [syslog-4648](../Parsers/parserContent_syslog-4648.md)
* [syslog-4768-ch](../Parsers/parserContent_syslog-4768-ch.md)
* [syslog-4769-ch](../Parsers/parserContent_syslog-4769-ch.md)
* [syslog-4776-ch](../Parsers/parserContent_syslog-4776-ch.md)
* [syslog-5145-ch](../Parsers/parserContent_syslog-5145-ch.md)
* [syslog-5156-ch](../Parsers/parserContent_syslog-5156-ch.md)
* [syslog-5158](../Parsers/parserContent_syslog-5158.md)
* [syslog-json-4663](../Parsers/parserContent_syslog-json-4663.md)
* [syslog-json-4720](../Parsers/parserContent_syslog-json-4720.md)
* [syslog-json-4722](../Parsers/parserContent_syslog-json-4722.md)
* [syslog-json-4723](../Parsers/parserContent_syslog-json-4723.md)
* [syslog-json-4724](../Parsers/parserContent_syslog-json-4724.md)
* [syslog-json-4725](../Parsers/parserContent_syslog-json-4725.md)
* [syslog-json-4740](../Parsers/parserContent_syslog-json-4740.md)
* [syslog-json-4767](../Parsers/parserContent_syslog-json-4767.md)
* [syslog-json-member-added-2008](../Parsers/parserContent_syslog-json-member-added-2008.md)
* [syslog-microsoft-dhcp](../Parsers/parserContent_syslog-microsoft-dhcp.md)
* [sysmon-windows-dns-query](../Parsers/parserContent_sysmon-windows-dns-query.md)
* [u-4663](../Parsers/parserContent_u-4663.md)
* [u-4688](../Parsers/parserContent_u-4688.md)
* [u-680](../Parsers/parserContent_u-680.md)
* [u-member-added-2008](../Parsers/parserContent_u-member-added-2008.md)
* [u-member-removed-2008](../Parsers/parserContent_u-member-removed-2008.md)
* [win-powershell-command](../Parsers/parserContent_win-powershell-command.md)
* [windows-4768-1](../Parsers/parserContent_windows-4768-1.md)
* [windows-dns-network-connection](../Parsers/parserContent_windows-dns-network-connection.md)
* [windows-dns-query](../Parsers/parserContent_windows-dns-query.md)
* [windows-dns-query-1](../Parsers/parserContent_windows-dns-query-1.md)
* [windows-dns-query-3](../Parsers/parserContent_windows-dns-query-3.md)
* [windows-dns-response](../Parsers/parserContent_windows-dns-response.md)
* [windows-dns-response-1](../Parsers/parserContent_windows-dns-response-1.md)
* [windows-rdp-login](../Parsers/parserContent_windows-rdp-login.md)
* [wls-4624](../Parsers/parserContent_wls-4624.md)
* [wls-4625](../Parsers/parserContent_wls-4625.md)
* [wls-4663](../Parsers/parserContent_wls-4663.md)
* [wls-4688](../Parsers/parserContent_wls-4688.md)
* [wls-4720](../Parsers/parserContent_wls-4720.md)
* [wls-4723](../Parsers/parserContent_wls-4723.md)
* [wls-4724](../Parsers/parserContent_wls-4724.md)
* [wls-4725](../Parsers/parserContent_wls-4725.md)
* [wls-4726](../Parsers/parserContent_wls-4726.md)
* [wls-4740](../Parsers/parserContent_wls-4740.md)
* [wls-4768](../Parsers/parserContent_wls-4768.md)
* [wls-4769](../Parsers/parserContent_wls-4769.md)
* [wls-4771](../Parsers/parserContent_wls-4771.md)
* [wls-4776](../Parsers/parserContent_wls-4776.md)
* [wls-627](../Parsers/parserContent_wls-627.md)
* [wls-644](../Parsers/parserContent_wls-644.md)
* [wls-675](../Parsers/parserContent_wls-675.md)
* [wls-member-added-2008-notype](../Parsers/parserContent_wls-member-added-2008-notype.md)
* [wls-windows-privileged-access](../Parsers/parserContent_wls-windows-privileged-access.md)
* [xml-1102-1](../Parsers/parserContent_xml-1102-1.md)
* [xml-1310](../Parsers/parserContent_xml-1310.md)
* [xml-4622](../Parsers/parserContent_xml-4622.md)
* [xml-4624](../Parsers/parserContent_xml-4624.md)
* [xml-4624-1](../Parsers/parserContent_xml-4624-1.md)
* [xml-4625](../Parsers/parserContent_xml-4625.md)
* [xml-4625-1](../Parsers/parserContent_xml-4625-1.md)
* [xml-4648](../Parsers/parserContent_xml-4648.md)
* [xml-4649](../Parsers/parserContent_xml-4649.md)
* [xml-4662](../Parsers/parserContent_xml-4662.md)
* [xml-4662-jp](../Parsers/parserContent_xml-4662-jp.md)
* [xml-4663](../Parsers/parserContent_xml-4663.md)
* [xml-4672](../Parsers/parserContent_xml-4672.md)
* [xml-4673](../Parsers/parserContent_xml-4673.md)
* [xml-4674](../Parsers/parserContent_xml-4674.md)
* [xml-4674-1](../Parsers/parserContent_xml-4674-1.md)
* [xml-4688](../Parsers/parserContent_xml-4688.md)
* [xml-4719](../Parsers/parserContent_xml-4719.md)
* [xml-4738](../Parsers/parserContent_xml-4738.md)
* [xml-4742-jp](../Parsers/parserContent_xml-4742-jp.md)
* [xml-4767](../Parsers/parserContent_xml-4767.md)
* [xml-4768](../Parsers/parserContent_xml-4768.md)
* [xml-4769](../Parsers/parserContent_xml-4769.md)
* [xml-4769-1](../Parsers/parserContent_xml-4769-1.md)
* [xml-4776](../Parsers/parserContent_xml-4776.md)
* [xml-4778](../Parsers/parserContent_xml-4778.md)
* [xml-4779](../Parsers/parserContent_xml-4779.md)
* [xml-4800](../Parsers/parserContent_xml-4800.md)
* [xml-4801](../Parsers/parserContent_xml-4801.md)
* [xml-5136](../Parsers/parserContent_xml-5136.md)
* [xml-5137](../Parsers/parserContent_xml-5137.md)
* [xml-5139](../Parsers/parserContent_xml-5139.md)
* [xml-5141](../Parsers/parserContent_xml-5141.md)
* [xml-5145](../Parsers/parserContent_xml-5145.md)
* [xml-5145-1](../Parsers/parserContent_xml-5145-1.md)
* [xml-5156](../Parsers/parserContent_xml-5156.md)
* [xml-5157](../Parsers/parserContent_xml-5157.md)
* [xml-5158](../Parsers/parserContent_xml-5158.md)
* [xml-5478](../Parsers/parserContent_xml-5478.md)
* [xml-5861](../Parsers/parserContent_xml-5861.md)
* [xml-6272](../Parsers/parserContent_xml-6272.md)
* [xml-member-removed-2008](../Parsers/parserContent_xml-member-removed-2008.md)
* [xml-powershell-4104](../Parsers/parserContent_xml-powershell-4104.md)