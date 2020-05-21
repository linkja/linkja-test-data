# linkja-test-data
Test data to be used when trying out Linkja software

* crypto - contains copies of the linkja-crypto library for Windows or macOS.  Two versions exist:
	* public - used by the linkja-salt-engine and linkja-matching programs, this does not contain the project-specific secret.
	* secret - used by linkja-hashing, this has a project-specific secret embedded in it.  **NOTE** The secret is included, which means this version of the library should never be used for an actual project.
* hashing - sample data file, public key, and salt file to be used for hashing
* matching - private key to be used for matching
* salt-engine - a main file containing test sites (`sites.csv`), and a supplemental file for adding sites to an existing project (`extra-sites.csv`).