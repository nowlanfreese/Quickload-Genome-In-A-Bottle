### About ###

This IGB Quickload contains links to the Genome in a Bottle data.

### IGB Quickload ###

The IGB file igbDefaultPrefs.json includes information for default Quickloads available in IGB.
The Quickload URL in the current release of IGB igbDefaultPrefs.json points to: https://bitbucket.org/nfreese/quickload-genome-in-a-bottle/raw/release-v1.0.0/quickload/

In the event that this repository needs to be updated (for example, to fix a broken link in the annots.xml), 
updates should be made to main and tested before merging to the release-v1.0.0 release branch.
**Any changes made to the release-v1.0.0 branch on this repository will immediately affect the Quickload in IGB.**

A new branch should only be made in the event that the IGB Quickload format changes in such a way that previous Quickloads would no longer function.
In this event, a new branch would be created with a new version number, and igbDefaultPrefs.json would need to be updated to point at this version.

### Mirror ###

The igbDefaultPrefs.json also specifies a mirror on GitHub: https://raw.githubusercontent.com/nowlanfreese/Quickload-Genome-In-A-Bottle/release-v1.0.0/quickload/

The following instructions were used to create the mirror:

git clone --mirror https://github.com/exampleuser/repository-to-mirror.git

cd repository-to-mirror.git

git remote set-url --push origin https://github.com/exampleuser/mirrored

git fetch -p origin

git push --mirror

### Additional Information ###

For additional information about how to add an IGB Quickload see the [IGB User's Guide](https://wiki.transvar.org/display/igbman/Home).

For additional information about the Genome in a Bottle dataset see the [GIAB main page](https://www.nist.gov/programs-projects/genome-bottle).
