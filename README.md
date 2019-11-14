# rdkcmf-manifests
List of manifests that can be used with RDK-M build for various platforms

## How to include?
Add any one of the manifests into local_manifests directory of CMF repo
~~~~
repo init -u https://code.rdkcentral.com/r/manifests -b thud -m rdkv-nosrc.xml
git clone https://github.com/moorthy-bs/rdkcmf-manifest.git
mkdir -p .repo/local_manifests
cp rdkcmf-manifest/cmf-thud-freescale.xml .repo/local_manifests/
repo sync
~~~~
