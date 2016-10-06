# Portworx Catalogs for Rancher

This provides the ability to deploy Portworx Enterprise storage on every Rancher node in your cluster.

There are two types of templates available...
1. Launch portworx and use all available storage on a node
2. Launch portworx in "head-only" mode where it can provide storage to other containers, but will not consume any local storage

To use this, do the following:
* Go to the admin tab, then click on settings
* In the catalog section, click "Add Catalog"
* In the Name box, enter `Portworx`
* In the URL box, enter `https://github.com/portworx/rancher`

Contact us at support@portworx.com if you have any questions.
