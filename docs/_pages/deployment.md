---
title: "Sea-Pol Deployment"
layout: archive
permalink: /deployment/
---

The Sea-Pol radar is based in Greeley, Colorado, at Colorado State University. It can be deployed on ships and at remote field sites.
The radar is packaged in ISO-668 1C containers for transportability and ease of deployment.
An example of such a deployment is the 2019 PISTON-2 field campaign where Sea-Pol was shipped to Keelung, Taiwan, loaded onto the R/V Sally Ride and spent 22 days at sea in support of the campaign.

## Past Deployments
* October - November 2017, R/V Roger Revelle (San Diego -> Eastern Pacific -> San Diego)
* August - September - October 2018, R/V Thomas G Thompson (Kaohsiung City Taiwan -> Palau -> Kaohsiung Taiwan)
* September 2019, R/V Sally Ride (Keelung Taiwan -> Western Pacific -> Keelung Taiwan)

## Planned Deployment
* May - August 2022, at Yonaguni Japan

# Post-processing software
Raw radar products are post-processed to generate secondary products including rain rate and hydrometeor identification. Post-processing can be customized to suit the needs of field campaigns. Output data is written in CfRadial-compliant netCDF files. Data is transferred to remote locations using FTP, rsync or LDM. Quick-look images are generated and posted to a webserver for immediate access to the data.

# Local operations and Data Storage
The radar shelter provides workstations to operate the radar locally. Servers are available to run post-processing code. Local data storage is available to prevent data loss during network outages.
The radar is normally operated remotely through its network connection; connectivity of 10 Mbit/s is required for reliable remote operation.
