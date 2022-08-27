# ZIP.deeZNNutz

**What is a ZIP?** ZIP stands for Zenon Improvement Proposal. ZIP is a framework to provide structured facilitation of an idea to software upgrade.

ZIPs are fault tolerant.  There is no central repository or editor who accepts or rejects ZIPs.  They are proposed by the community to Pillars.  If a Pillar supports a ZIP they will broadcast that support by publishing the ZIP on github, gitlab, IPFS, or some other public broadcast channel with a numbering system.  If other Pillars support the iniative they will signal support by referencing the the ZIP proposal in their own public broadcast channel. The Zenon community will maintain a "ZIP Pointer Service" repository which points to all the available dZIP broadcast channels supported by Pillars. This Pointer Service is centrally managed and provided as an administrative function by the Zenon community to make it easier to search all ZIPs.  
> Proposed Naming Convention:  ZIP:[Pillar Name]-[Number]

# General Notes

- ZIPs do not need to follow a standard structure unless we intend to write tooling. Pillar can develop their own ZIP standards or structured metadata.
- ZIPs should be formally introduced via a sponsoring Pillar. Sponsorship implies that the pillar will vote for it, and ultimately upgrade software if needed. A change that cannot find a sponsor is either underdeveloped or dead on arrival.
- Changes that no pillar cares about are arguably out of scope of the ZIP framework.
- Pillars can introduce/sponsor ZIPs by hosting it in their own git repo. They can verify ownership by including a signature in the repo.
- ZIPs should follow a sequential numbering scheme: ZIP:[Pillar Name]-[Number]
- Pillars and supporters can mirror the repo for data redundancy, ideally on other platforms
- Pillars should consider mirring their own respoitories on central services to offsite locations for resiliance.
- The ZIP Pointer Service will maintain an official pointer repo, verify pillar ownership of the ZIP repos (through signature file), and add as submodule. The only subjective decision making needed is for abuse from pillars, eg obscene content
- Long term goal is to move ZIPs on-chain

Source: https://github.com/orgs/Big-Inches-Club-House/discussions/4
