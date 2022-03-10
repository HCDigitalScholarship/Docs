# Equipment 

There are three main categories of equipment managed by the DS program.  The first are physical computers used by students for development work. The secon are Linux virtual machines maintained by campus IT (IITS) and Adam Portier.  The campus VMs are used for production versions of long-term DS projects. We are very lucky to have access to campus IT resources and we typically only deploy or update fisnished projects to these servers.  For development servers and a general low-stakes sandbox, we used VMs from Digital Ocean.  As a courtesy to our partners in IT, we have also used DO VMs for production servers.  Several haverford.edu subdomains point to DO VMs.  These were created with a request to prodesk@haverford.edu after consulting with Communications. DS is responsible for the updating and security of these VMs.  We are also responsible for renewing ssl certifications for https. 

## Computers 
- BADL 
- Macbooks 

## Virtual Machines 

### Haverford IITS VMs (see Adam Portier)

| domain                          | ip              | https | status      | partner           | repository                                                        | notes                              |
|---------------------------------|-----------------|-------|-------------|-------------------|-------------------------------------------------------------------|------------------------------------|
| ds-wordpress.haverford.edu      | 165.82.124.20   | FALSE |             |                   |                                                                   |                                    |
| ds-carbonite.haverford.edu      | 165.82.124.23   | FALSE | active      |                   |                                                                   | legacy projects                    |
| ticha.haverford.edu             | 165.82.124.24   | TRUE  |             | Brook Lillehaugen | https://github.com/HCDigitalScholarship/ticha-django-site         |                                    |
| pennstreaty.haverford.edu       | 165.82.124.27   | TRUE  |             | Sara Horowitz     | https://github.com/HCDigitalScholarship/QI                        |                                    |
| gtrp.haverford.edu              | 165.82.124.28   | FALSE | production  | Barak Mendelsohn  | https://github.com/HCDigitalScholarship/global-terrorism-research |                                    |
| digitalduchemin.org             | 165.82.124.31   | FALSE | production  | Rich Freedman     |                                                                   |                                    |
| quakerexplorer.haverford.edu    | 165.82.124.33   | FALSE |             | Mary Crauderueff  |                                                                   |                                    |
| digitalpedagogy.haverford.edu   | 165.82.124.39   | FALSE |             | Terry Snyder      | WordPress                                                         |                                    |
| oer.haverford.edu               | 165.82.124.49   | TRUE  |             |                   | PressBooks                                                        |                                    |
| dev-solidarity.haverford.edu    |                 | FALSE | active      |                   |                                                                   | Solidarity Economy Map             |
| ds-web.haverford.edu            |                 | FALSE | retired     |                   |                                                                   |                                    |
| qmh.haverford.edu               |                 | FALSE | production  | Mary Crauderueff  | https://github.com/HCDigitalScholarship/QMH                       |                                    |
| ds-omeka.haverford.edu          |                 | FALSE | retired     |                   | Omeka                                                             | legacy omeka projects              |
| ds-crim.haverford.edu           | 165.82.124.42   | TRUE  | active      | Rich Freedman     | JupyterHub                                                        |                                    |
| http://cope.haverford.edu/      | 165.227.217.17  | FALSE |             | Mary Crauderueff  | https://github.com/HCDigitalScholarship/cope-evans                |                                    |
| Quakers and Travel dev          | 167.71.95.205   |       | development | Mary Crauderueff  | https://github.com/HCDigitalScholarship/Quaker-Travels            |                                    |
| necrology.haverford.edu/        | 134.209.121.250 | FALSE | production  |                   | https://github.com/HCDigitalScholarship/quaker-necrology          |                                    |
| GreekPal                        | 165.22.186.240  | FALSE | development | Darin Hayton      |                                                                   |                                    |
| Quakers and the Holocaust       | 165.22.186.240  | TRUE  | development | David Watt        | https://github.com/HCDigitalScholarship/QH                        |                                    |
| Dictionary of Quaker Biography  | 198.211.117.101 | FALSE | development | Mary Crauderueff  | https://github.com/HCDigitalScholarship/DQB                       |                                    |
| CRIM-dev                        | 159.65.177.99   |       | development |                   |                                                                   | RETIRE                             |
| QI-dev                          | 159.203.172.178 |       | development |                   |                                                                   | RETIRE                             |
| Bridge-dev                      | 104.131.190.90  |       | development |                   |                                                                   | RETIRE                             |
| Cope Evans                      | 167.99.144.125  |       | legacy      | Mary Crauderueff  | https://github.com/HCDigitalScholarship/CopeEvans                 | old version of site, why running?  |
| Ticha-dev                       | 192.241.146.226 |       | development |                   |                                                                   | RETIRE                             |
| GreekPal-dev, BoD, dashboard    | 142.93.193.243  |       |             |                   |                                                                   | RETIRE                             |
| Cope Evans                      | 165.227.217.17  |       |             |                   |                                                                   |                                    |
| Old Version of the Bridge       | 157.230.91.119  |       | legacy      | Bret Mulligan     |                                                                   |                                    |

### Digital Ocean Dropets
| domain                                        | ip              | https | status      | partner                    | repository                                                   | notes                                                |
|-----------------------------------------------|-----------------|-------|-------------|----------------------------|--------------------------------------------------------------|------------------------------------------------------|
| migrantvoices.haverford.edu                   | 147.182.213.25  | TRUE  | development | Anita Issacs, Anne Preston | https://github.com/HCDigitalScholarship/migration-encounters | moving to WordPress, this can be retired soon        |
| bridge.haverford.edu                          | 64.227.97.179   | TRUE  | production  | Bret Mulligan              | https://github.com/HCDigitalScholarship/FastBridge           | FastAPI                                              |
| archivogam.haverford.edu                      | 192.241.128.56  | TRUE  | production  | Carlos Juárez              | https://github.com/HCDigitalScholarship/GAM                  | Django, with significant assets in DO object storage |
| crimproject.org                               | 167.99.13.5     | TRUE  | production  | Rich Freedman              | https://github.com/CRIM-Project/CRIM-online                  | Django                                               |
| booksofduchesses.com                          | 67.207.92.242   | TRUE  | production  | Sarah Watson               | https://github.com/HCDigitalScholarship/booksofduchesses     | this is being retired                                |
| islaminchina.org                              | 167.99.0.192    | TRUE  | development | Guangtian Ha               | https://github.com/HCDigitalScholarship/islam-in-china       | FastAPI                                              |
| economicsexperiment.com                       | 147.182.213.25  | FALSE | production  | Haya Goldblatt             | https://github.com/HCDigitalScholarship/fuzzytext            | Django                                               |
| cobbswatershed.org                            | 162.243.175.124 | FALSE | production  | Josh Moses                 | WordPress                                                    | could be moved to sites.haverford                    |
| manumissions.haverford.edu                    | 68.183.124.230  | TRUE  | production  | Mary Crauderueff           | https://github.com/HCDigitalScholarship/manumissions         | Django                                               |
|                                               |                 |       |             |                            |                                                              |                                                      |
| Quakers and Mental Health site in development | 137.184.59.75   | FALSE | develpment  | Mary Crauderueff           | https://github.com/HCDigitalScholarship/qmh-v2               |                                                      |
| civicengagementmap.haverford.edu              | 147.182.213.25  | TRUE  | develpment  | CPGC                       | https://github.com/HCDigitalScholarship/civic-engagement-map | retired, moving Drupal w/ Communcations              |
| Beyond Penn's Treaty in development           | 104.131.31.182  | FALSE | develpment  | Sarah Horowitz             | https://github.com/HCDigitalScholarship/penn-treaty-v2       |                                                      |
|                                               |                 |       |             |                            |                                                              |                                                      |
| CRIM development copy                         | 161.35.0.93     | FALSE | development | Rich Freedman              |                                                              | RETIRE                                               |
| Quakers and Travel dev                        | 167.71.95.205   |       | development | Mary Crauderueff           | https://github.com/HCDigitalScholarship/Quaker-Travels       |                                                      |
| necrology.haverford.edu/                      | 134.209.121.250 | FALSE | production  |                            | https://github.com/HCDigitalScholarship/quaker-necrology     |                                                      |
| GreekPal                                      | 165.22.186.240  | FALSE | development | Darin Hayton               |                                                              |                                                      |
| Quakers and the Holocaust                     | 165.22.186.240  | TRUE  | development | David Watt                 | https://github.com/HCDigitalScholarship/QH                   |                                                      |
| Dictionary of Quaker Biography                | 198.211.117.101 | FALSE | development | Mary Crauderueff           | https://github.com/HCDigitalScholarship/DQB                  |                                                      |
| CRIM-dev                                      | 159.65.177.99   |       | development |                            |                                                              | RETIRE                                               |
| QI-dev                                        | 159.203.172.178 |       | development |                            |                                                              | RETIRE                                               |
| Bridge-dev                                    | 104.131.190.90  |       | development |                            |                                                              | RETIRE                                               |
| Cope Evans                                    | 167.99.144.125  |       | legacy      | Mary Crauderueff           | https://github.com/HCDigitalScholarship/CopeEvans            | old version of site, why running?                    |
| Ticha-dev                                     | 192.241.146.226 |       | development |                            |                                                              | RETIRE                                               |
| GreekPal-dev, BoD, dashboard                  | 142.93.193.243  |       |             |                            |                                                              | RETIRE                                               |
| Cope Evans                                    | 165.227.217.17  |       |             |                            |                                                              |                                                      |
| Old Version of the Bridge                     | 157.230.91.119  |       | legacy      | Bret Mulligan              |                                                              |                                                      |

## Other stuff