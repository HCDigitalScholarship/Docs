# Equipment 

There are three main categories of equipment managed by the DS program.  The first are physical computers used by students for development work. The secon are Linux virtual machines maintained by campus IT (IITS) and Adam Portier. The campus VMs are used for production versions of long-term DS projects. We are very lucky to have access to campus IT resources and we typically only deploy or update fisnished projects to these servers. For development servers and a general low-stakes sandbox, we used VMs from Digital Ocean. As a courtesy to our partners in IT, we have also used DO VMs for production servers. Several haverford.edu subdomains point to DO VMs. These were created with a request to prodesk@haverford.edu after consulting with Communications. DS is responsible for the updating and security of these VMs.  We are also responsible for renewing ssl certifications for https. 

## Computers 
- The BADL (Badass Deep Learning Machine) is a computer built by student Dylan Emory to facilitate work in machine learning. It has two drives. The first is a 500G SSD drive used for the operating system. There is also a 4T drive called "Storage" that is used for large datasets. The GAM archive materials are held on that drive. This includes the original Baggit files transferred from Guatemala. The DIP files from Archivematica, and the dzi files. I think this drive needs to be re-mounted if you don't see it in the filesystem. There have also been issues with the RAM. Two boards failed in 2019 and were replaced by the manufacturer.  Recently the RAM has gone from 64G to 42G, so there is likely another failed board or two.  

- Macbooks. There are two Macbook pros that were recently purchased for use by students. In theory, they provide a workspace with all the necessary programs for development work.  In practice, most students prefer to work on their own machines.  Several of our projects are currently too complicated to install locally and have their own digital ocean droplets as dev servers. 

- Slack. DS maintains a Slack organization that is used widely across the Libraries. It should probably be used as Libraries Slack rather than just DS. haverfordds.slack.com  There is also trico-ds.slack.com

- GitHub. 
  - There is a GitHub organization for DS projects: https://github.com/orgs/HCDigitalScholarship
  - Internal docs including passwords and such are here: https://github.com/HCDigitalScholarship/internal-docs
  - The "DS Cookbook" with common solution and processes is here: https://github.com/HCDigitalScholarship/ds-cookbook
  
  - Also one for Tri-co DS: https://github.com/orgs/tri-cods
  - KeystoneDH: https://github.com/orgs/KeystoneDH
  - CRIM-Project: https://github.com/orgs/CRIM-Project


## Virtual Machines 

### Haverford IITS VMs (see Adam Portier)
| domain                        | ip             | partner           | repository                                                        | notes                    |
|-------------------------------|----------------|-------------------|-------------------------------------------------------------------|--------------------------|
| ds-wordpress.haverford.edu    | 165.82.124.20  |                   |                                                                   |                          |
| ds-carbonite.haverford.edu    | 165.82.124.23  |                   |                                                                   | legacy projects          |
| ticha.haverford.edu           | 165.82.124.24  | Brook Lillehaugen | https://github.com/HCDigitalScholarship/ticha-django-site         |                          |
| pennstreaty.haverford.edu     | 165.82.124.27  | Sara Horowitz     | https://github.com/HCDigitalScholarship/QI                        |                          |
| gtrp.haverford.edu            | 165.82.124.28  | Barak Mendelsohn  | https://github.com/HCDigitalScholarship/global-terrorism-research |                          |
| digitalduchemin.org           | 165.82.124.31  | Rich Freedman     |                                                                   | Rich Freedman            |
| quakerexplorer.haverford.edu  | 165.82.124.33  | Mary Crauderueff  |                                                                   |                          |
| digitalpedagogy.haverford.edu | 165.82.124.39  | Terry Snyder      | WordPress                                                         |                          |
| oer.haverford.edu             | 165.82.124.49  |                   | PressBooks                                                        |                          |
| dev-solidarity.haverford.edu  |                |                   |                                                                   | Solidarity Economy Map   |
| ds-web.haverford.edu          |                |                   |                                                                   |                          |
| qmh.haverford.edu             |                | Mary Crauderueff  | https://github.com/HCDigitalScholarship/QMH                       |                          |
| ds-omeka.haverford.edu        |                |                   | Omeka                                                             | legacy omeka projects    |
| ds-crim.haverford.edu         | 165.82.124.42  | Rich Freedman     | JupyterHub                                                        | Rich Freedman JupyterHub |
| cope.haverford.edu            | 165.227.217.17 | Mary Crauderueff  | https://github.com/HCDigitalScholarship/cope-evans                |                          |

### Digital Ocean Dropets
| domain                                        | ip              | partner                    | repository                                                   | notes                    |
|-----------------------------------------------|-----------------|----------------------------|--------------------------------------------------------------|--------------------------|
| beyondborders.haverford.edu                   | 147.182.213.25  | Anita Issacs, Anne Preston | https://github.com/HCDigitalScholarship/migration-encounters |                          |
| bridge.haverford.edu                          | 64.227.97.179   | Bret Mulligan              | https://github.com/HCDigitalScholarship/FastBridge           | legacy projects          |
| archivogam.haverford.edu                      | 192.241.128.56  | Carlos Juárez              | https://github.com/HCDigitalScholarship/GAM                  |                          |
| crimproject.org                               | 167.99.13.5     | Rich Freedman              | https://github.com/CRIM-Project/CRIM-online                  |                          |
| booksofduchesses.com                          | 67.207.92.242   | Sarah Watson               | https://github.com/HCDigitalScholarship/booksofduchesses     |                          |
| islaminchina.org                              | 167.99.0.192    | Guangtian Ha               | https://github.com/HCDigitalScholarship/islam-in-china       | Rich Freedman            |
| economicsexperiment.com                       | 147.182.213.25  | Haya Goldblatt             | https://github.com/HCDigitalScholarship/fuzzytext            |                          |
| cobbswatershed.org                            | 162.243.175.124 | Josh Moses                 | WordPress                                                    |                          |
| manumissions.haverford.edu                    | 68.183.124.230  | Mary Crauderueff           | https://github.com/HCDigitalScholarship/manumissions         |                          |
|                                               |                 |                            |                                                              | Solidarity Economy Map   |
| Quakers and Mental Health site in development | 137.184.59.75   | Mary Crauderueff           | https://github.com/HCDigitalScholarship/qmh-v2               |                          |
| civicengagementmap.haverford.edu              | 147.182.213.25  | CPGC                       | https://github.com/HCDigitalScholarship/civic-engagement-map |                          |
| Beyond Penn's Treaty in development           | 104.131.31.182  | Sarah Horowitz             | https://github.com/HCDigitalScholarship/penn-treaty-v2       | legacy omeka projects    |
|                                               |                 |                            |                                                              | Rich Freedman JupyterHub |
| CRIM development copy                         | 161.35.0.93     | Rich Freedman              |                                                              |                          |
| Quakers and Travel dev                        | 167.71.95.205   | Mary Crauderueff           | https://github.com/HCDigitalScholarship/Quaker-Travels       |                          |
| necrology.haverford.edu/                      | 134.209.121.250 |                            | https://github.com/HCDigitalScholarship/quaker-necrology     |                          |
| GreekPal                                      | 165.22.186.240  | Darin Hayton               |                                                              |                          |
| Quakers and the Holocaust                     | 165.22.186.240  | David Watt                 | https://github.com/HCDigitalScholarship/QH                   |                          |
| Dictionary of Quaker Biography                | 198.211.117.101 | Mary Crauderueff           | https://github.com/HCDigitalScholarship/DQB                  |                          |
| CRIM-dev                                      | 159.65.177.99   |                            |                                                              |                          |
| QI-dev                                        | 159.203.172.178 |                            |                                                              |                          |
| Bridge-dev                                    | 104.131.190.90  |                            |                                                              |                          |
| Cope Evans                                    | 167.99.144.125  | Mary Crauderueff           | https://github.com/HCDigitalScholarship/CopeEvans            |                          |
| Ticha-dev                                     | 192.241.146.226 |                            |                                                              |                          |
| GreekPal-dev, BoD, dashboard                  | 142.93.193.243  |                            |                                                              |                          |
| Cope Evans                                    | 165.227.217.17  |                            |                                                              |                          |
| Old Version of the Bridge                     | 157.230.91.119  | Bret Mulligan              |                                                              |                          |

## Other stuff