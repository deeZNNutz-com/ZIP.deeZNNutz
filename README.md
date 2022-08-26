# dZIP.deeZNNutz

**What is an a dZIP?** dZIP stands for distributed Zenon Improvement Proposal. dZIP is a framework to provide structured facilitation of an idea to software upgrade.

dZIPs are fault tolerant.  There is no central repository or editor who accepts or rejects dZIPs.  dZIPs are proposed by the community to Pillars.  If a Pillar supports a dZIP they will broadcast that support by publishing the dZIP on github, gitlab, IPFS, or some other public broadcast channel with a numbering system.  If other Pillars support the iniative they will signal support by referencing the the dZIP proposal in their own public broadcast channel. The Zenon community will maintain a "dZIP Pointer Service" repository which points to all the available dZIP broadcast channels supported by Pillars. This Pointer Service is centrally managed and provided as an administrative function by the Zenon community to make it easier to search all dZIPs.  
> Proposed Naming Convention:  dZIP:[Pillar Name]-[Number]

General Notes:

- dZIPs do not need to follow a standard structure unless we intend to write tooling.  The Pillar supporing a dZIP can implement their own standards or structured metadata.
- dZIPs should be formally introduced via a sponsoring Pillar. Sponsorship implies that the pillar will vote for it, and ultimately upgrade software if needed. A change that cannot find a sponsor is either underdeveloped or dead on arrival.
- Changes that no pillar cares about are arguably out of scope of the dZIP framework.
- Pillars can introduce/sponsor dZIPs by hosting it in their own git repo. They can verify ownership by including a signature in the repo. 
- dZIPs should follow a sequential numbering scheme: dZIP:[Pillar Name]-[Number]
- Pillars and supporters can mirror the repo for data redundancy, ideally on other platforms
- Pillars should consider mirring their own respoitories on central services to offsite locations for resiliance.
- The dZIP Pointer Service will maintain an official pointer repo, verify pillar ownership of the dZIP repos (through signature file), and add as submodule. The only subjective decision making needed is for abuse from pillars, eg obscene content
- Long term goal is to move dZIPs on-chain


Source: https://github.com/orgs/Big-Inches-Club-House/discussions/4
