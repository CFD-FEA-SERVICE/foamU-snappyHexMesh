# CASES TO ADD
* Inflation layer
* Sharp point (triple point)
* Import part of cfMesh into snappy (BL)

# RULES TO ADD NEW CASES
* Each mesh MUST have all the input dictionaries to generate the mesh WITHOUT any modification by the user
* SCRIPT -> Add an Allrun script to generate the mesh (this must call blockMesh, snappyHexMesh, etc. etc.)
* OF version: each CASENAME must have a suffix which indicates the OF versions to use. Example: motorBike-9, motorBike-2412, motorBike-12
* Only OpenFOAM.com and OpenFOAM.org versions are accepted
* MESH size < 0.5M cells
* MESH generation time < 3 minutes
