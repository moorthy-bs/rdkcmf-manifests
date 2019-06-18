# rdkcmf-manifests
List of manifests that can be used with RDK-M build for various platforms

## How to include?
Add any one of the manifests into local_manifests directory of CMF repo
~~~~
repo init https://code.rdkcentral.com/r/manifests -b rdk-next -m rdkv-asp-nosrc.xml
mkdir -p .repo/local_manifests
cp cmf-thud-freescale.xml .repo/local_manifests
repo sync
~~~~
