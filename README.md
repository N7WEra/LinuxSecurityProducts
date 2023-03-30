# LinuxSecurityProducts

A Table with Linux Securiy products and the corspending service name / Process name.

|     **Product**                     |     Service name        |     Process name |     Notes                                                                                                                         |     Version file                                                             |
|-------------------------------------|-----------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|
|     Bitdefender                     |     bdsec*                  |                      |     https://www.bitdefender.com/business/support/en/77209-157515-bitdefender-endpoint-security-tools-for-linux-quick-start-guide.html |                                                                                  |
|     CrowdStrike                     |     falcon-sensor.service   |     falcon-sensor    |     https://www.crowdstrike.com/blog/tech-center/install-falcon-sensor-for-linux/                                                     |     /opt/CrowdStrike/falconctl —version                                          |
|     Elastic Security                |     elastic-agent           |     elastic-agent    |     https://www.elastic.co/guide/en/fleet/current/start-stop-elastic-agent.html                                                       |     elastic-agent version                                                        |
|     Filebeat                        |     filebeat.service        |                      |                                                                                                                                       |                                                                                  |
|     Kaspersky  endpoint security    |     kesl-supervisor         |                      |     https://support.kaspersky.com/kes4linux/10sp1/en-US/161252.htm                                                                    |                                                                                  |
|     Microsoft defender for endpoint |     mdatp.service           |                      |     https://learn.microsoft.com/en-us/microsoft-365/security/defender-endpoint/linux-support-install?view=o365-worldwide              |                                                                                  |
|     Rapid7 Insight                  |     ir_agent                |                      |     https://docs.rapid7.com/insight-agent/agent-controls/#linux                                                                       |     sudo cat   /opt/rapid7/ir_agent/components/insight_agent/common/agent.log    |
|     Rapid7 InsightVM                |     nexposeconsole          |                      |     https://docs.rapid7.com/insightvm/service-start-stop-and-status-controls/                                                         |                                                                                  |
|     Red Canary                      |     cfsvcd                  |                      |     https://help.redcanary.com/hc/en-us/articles/360052513614-Deploy-an-EDR-sensor-agent                                              |                                                                                  |
|     Sophos                          |                             |                      |                                                                                                                                       |     /opt/sophos-av/plugins/av/VERSION.ini                                        |
|     Splunk                          |     SplunkForwarder.service |                      |                                                                                                                                       |                                                                                  |
|     Tanium                          |     taniumclient            |                      |     https://docs.tanium.com/client/client/managing.html#linux                                                                         |                                                                                  |
|     Telegraf                        |     telegraf.service        |                      |                                                                                                                                       |                                                                                  |
|     Trend Micro Deep Security       |                             |     ds_agent         |     https://help.deepsecurity.trendmicro.com/10/0/Get-Started/Install/agent-deactivate-start-stop.html                                |                                                                                  |
|     VMware  Carbon Black            |     cbagentd                |                      |     https://community.carbonblack.com/t5/Knowledge-Base/Carbon-Black-Cloud-How-to-Stop-Start-the-Linux-Daemons/ta-p/62500             |     /opt/carbonblack/psc/bin/cbagentd ––version                                  |
|     Zabbix                          |     zabbix-agent2.service   |                      |                                                                                                                                       |                                                                                  |
