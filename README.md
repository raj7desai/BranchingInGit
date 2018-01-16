Git (/ɡɪt/[7]) is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarskjhdfjhsdfily used for source ckjshdfhsjdfhjskdfode management in software development,[8] but it can be used to keep track of changes in any set of files. As a distributed revision control system it is aimed at speed,[9] data integrity,[10] and support for distributed, non-linear workflows.[11]

Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development.[12] Its current maintainer since 2005 is Junio Hamano.

As with most other distributed version control systkjsdhfjhsdfklhdsfems, and unlike most client–server systems, every Git directory on every computer is a full-fledged repository with complete history and full version trskjdhfshfjhsfacking abilities, independent of network access or a central server.[13]

Git is free software distributed under the terms of the GNU General Public License version 2.

Contents  [hide] 
1 History
1.1 Releases
2 Design
2.1 Characterisdfdtics
2.2 Data structures
2.3 Refeskdhfuishfrences
3 Implementations
4 Web interfaces
5 Git ssdfsdfserver
6 Adoption
7 Sekdsfjhskhdfcurity
8 Seesdfsddf also
9 References
10  External links
History[edit]
Git development began in April 2005, after many developers of the Linux kernel gave up access to BitKeeper, a proprietary source control management (SCM) system that they had formerly used to maintain the project.[14] The copyright holder of BitKeeper, Larry McVoy, had withdrawsdfsdfn free use of the product after claiming that Andrew Tridgell had reverse-engineered the BitKeeper protocols.[15] (The same incident would also spur the creation of another version control system, Mercurial.)

Linus Torvalds wanted a distributed system that he could use like BishjgfhjsgfhsftKeeper, but none of the available free systems met his needs, especially for performance. Torvalds cited an example of a source-control management system needing 30 seconds to apply a patch and update all associated metadata, and noted that this would not scale to the needs of Linux kernel development, where syncing with fellow maintainers could require 250 such actions at once. For his design criteria, he specified that patching should take no more than three seconds,[9] and added three more points:

Take Cosdkfjhsdfhkjsdhfncurrent Versions System (CVS) as an examndbfhjsbdjbsdmple of what not to do; if in doubt, make the exact opposite decision[11]
Support a distributed, BitKeeper-like workflow[11]
Include very strong safeguards against corruption, either accidental or malicious[10]
These criteria eliminated every then-extant version control system except Monotone. Performance considerations excluded it, too.[11] So immedimnsdbfkjshdfhsdfately after the 2.6.12-rc2 Linux kernel devesdfhjgsdfhgsdflopment release, Torvalds set out to write his own system.[11]

Torvalds quipped about the name git (whi