# ocpjbod
ocpjbod is a SCSI enclosure management tool that controls some OCP
storage enclosure, like Open Vault (Knox).

## Examples
ocpjbod list
ocpjbod hdd --hdd-on 0 /dev/sg1
ocpjbod sensor /dev/sg1

## Requirements
ocpjbod requires or works with
* Linux
* sg3_utils-libs (>= 1.28)

## Building ocpjbod
Simply use make.

## Installing ocpjbod
Run make install.

## How ocpjbod works
ocpjbod controls SCSI enclosure through SES commands and SCSI read/write
buffer commands

## License
ocpjbod is BSD-licensed. We also provide an additional patent grant.