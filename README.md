### About ###

This IGB Quickload contains links to the Genome in a Bottle data.

For more information about this data see the Genome in a Bottle [main page](https://jimb.stanford.edu/giab), 
[NIST page](https://www.nist.gov/programs-projects/genome-bottle), or 
[publication](https://pubmed.ncbi.nlm.nih.gov/24531798/).

### IGB Quickload ###

This QuickLoad site is hosted on http://bioviz.org/quickload/genome-in-a-bottle/

A mirror is hosted on https://bitbucket.org/nfreese/quickload-genome-in-a-bottle/raw/release-v1.0.0/quickload/


### How to update this Quickload ###
In the event that this repository needs to be updated (for example, to fix a broken link in the annots.xml), 
updates should be made to the BitBucket [main branch](https://bitbucket.org/nfreese/quickload-genome-in-a-bottle/src/main/) and 
tested before merging to the [release-v1.0.0 branch](https://bitbucket.org/nfreese/quickload-genome-in-a-bottle/src/release-v1.0.0/).

An Ansible playbook can then be run to update the Quickload at http://bioviz.org/quickload/genome-in-a-bottle/ 

A new branch should only be made in the event that the IGB Quickload format changes in such a way that previous Quickloads would no longer function.
In this event, a new branch would be created with a new version number, and igbDefaultPrefs.json would need to be updated to point at this version.


### Additional Information ###

For additional information about how to add an IGB Quickload see the [IGB User's Guide](https://wiki.transvar.org/display/igbman/Home).
