### :exclamation: Disclaimer
- This Repo is a mirror of various internal MIB files from various Cisco Repos.
- All changes **MUST** be modified at the source and then replicated out to this repo.
- This guide details how this repo handles Pull Requests, Issues and Application support to that all involved are on the same page.

### :repeat: Pull Requests
- **ONLY** Pull requests from Cisco Systems employees will be accepted. See the [Internal Contributing Page](https://wiki.cisco.com/display/IOXXECHASA/SNMP+MIB+Publishing+guidelines) for the full process.
- Acceptable pull requests from 3rd parties will be converted to an Cisco Defect e.g `CSCxyz1234` to update the internal repository.
  - This will be referenced in an issue for the same change.
- All pull requests require an code review and approval before merging by an [individual with commit privledges](https://github.com/orgs/cisco/teams/cisco-mib-commit/members).
- Pull requests for the `v2/CISCO-PRODUCTS-MIB.my`, `v2/CISCO-ENTITY-VENDORTYPE-OID-MIB.my` are owned by the Cisco SNMP Team and all PRs **MUST** be created by them.

### :beetle: Issues
- Issues with MIB files may be raised on this Repo. 
  - This includes syntax issues, missing values, missing imports or other general problems with the files.
- For Syntax issues please include `smilint` output.
  - Errors 0-2 will be converted to Cisco Defects for the appropriate Cisco development team to triage.
  - Errors 3-6 will be triaged a defect filed if it is deemed to be required.
  - Reference: [SMILINT Error Levels](https://www.ibr.cs.tu-bs.de/projects/libsmi/smilint.html)
 
### :mag: SNMP / Application Support
- Please consult with the [Cisco Technical Assistance Center (TAC)](https://www.cisco.com/c/en/us/support/web/tsd-cisco-worldwide-contacts.html) or [Support Forums](https://community.cisco.com/t5/network-management/bd-p/5931-discussions-network-management).
- Issues of this type will be closed and a note redirecting to the worldwide contacts.