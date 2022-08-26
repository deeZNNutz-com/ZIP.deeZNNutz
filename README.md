# dZIP.deeZNNutz

**What is an a dZIP?** dZIP stands for distributed Zenon Improvement Proposal. dZIP is a framework to provide structured facilitation of an idea to software upgrade.

dZIPs are fault tolerant.  There is no central repository or editor who accepts or rejects dZIPs.  dZIPs are proposed by the community to Pillars.  If a Pillar supports a dZIP they will broadcast that support by publishing the dZIP on github, gitlab, IPFS, or some other public broadcast channel with a numbering system.  If other Pillars support the iniative they will signal support by referencing the the dZIP proposal in their own public broadcast channel. The Zenon community will maintain a "dZIP Pointer Service" repository which points to all the available dZIP broadcast channels supported by Pillars. This Pointer Service is centrally managed and provided as an administrative function by the Zenon community to make it easier to search all dZIPs.  
> Proposed Naming Convention:  dZIP:[Pillar Name]-[Number]

General Notes:

- dZIPs do not need to follow a standard structure unless we intend to write  .  The Pillar supporing a dZIP might implement their own standards or structured metadata.


The documents don’t really need to follow a standard structure or provide a structured metadata unless we are writing tooling to use them
People are used to single central repository with a few editors/curators; this is easy to find and navigate
But this places a subjective burden on editors on what to include and also creates a single point that can very easily be disrupted
With recent events, it seems many other projects are questioning their reliance on central repositories and maintainers
Long term, ideally we use services built on top the network, but we’re not there yet
In theory my decentralized ideal would be immutable documents hosted via something like bittorrent or ipfs, where anyone can collectively support the storage/retrieval of things they want to share. Anyone would be able to curate/compile lists for others to reference since they all point to the same things
These documents are pretty small in size and such granularity of data replication is likely not needed
Git repositories are the expected de facto standard interface and provide decentralized data replication mechanisms
Git repositories support submodules to include other repositories
Our network governance is done through Pillars as representatives.
We can draw from real world representative governance; proposed legislation must be sponsored/introduced by a representative
This is a logical requirement because any proposals that aren’t able to find a sponsoring representative are either Dead on Arrival, or worse: voted on without anyone’s understanding. Sponsorship is reputation skin in the game
My suggestion is thus that all ZIPs must be formally introduced via a sponsoring Pillar. Sponsorship implies that the pillar will vote for it, and ultimately upgrade software if needed. A change that cannot find a sponsor is either underdeveloped or dead on arrival.
Changes that no pillar cares about are also arguably out of scope of the ZIP framework
Pillars can introduce/sponsor ZIPs by hosting it in their own git repo. They can verify ownership by including a signature in the repo. Ideally they follow a sequential numbering scheme with file naming
This creates a convenient and unique identification scheme: ZIP <sponsor name>: <file path>
Supporters can mirror the repo for data redundancy, ideally on other platforms
Aggregation can be done by anyone through pointer repos that include zip repos through git submodules
The role of optional official editors: maintain an official pointer repo, verify pillar ownership of their zip repos (through signature file), and add as submodule. The only subjective decision making needed is for abuse from pillars, eg obscene content



## Proof of Pillar
Insert Signed Message Confirming Proof of Pillar
