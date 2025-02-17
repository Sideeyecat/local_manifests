# Buildable repositories for SM6225-Motorola (devon - hawao - rhode)
======================================================================

Starting from zero:
---------
    # cd into your ROM's folder
    repo init {Rom-Sources}
    mkdir -p .repo/local_manifests
    curl https://raw.githubusercontent.com/SM6225-Motorola/local_manifests/main/motorola-sm6225.xml > .repo/local_manifests/motorola-sm7325.xml
    repo sync


If you've already synced Rom-Sources:
----------
    # cd into your ROM folder
    mkdir -p .repo/local_manifests
    curl https://raw.githubusercontent.com/SM6225-Motorola/local_manifests/main/motorola-sm6225.xml > .repo/local_manifests/motorola-sm7325.xml
    repo sync