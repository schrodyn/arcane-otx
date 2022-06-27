# Arcane Observatory - Alienvault OTX Synapse Package

Made with love and tears for the Arcane Observatory.

This is a Synapse Storm [Package](https://synapse.docs.vertex.link/en/latest/synapse/glossary.html#gloss-package) developed to implement the [Alientvault OTX API](https://otx.alienvault.com/api). This is unstable and as your own risk. There is assumed knowledge of the user and is provided without support.

## Permissions
Various rules (permissions) are required to operate the package. I.e.:

* node.add
* tag.add
* edge.add
* node.prop.set

To use the package itself the cortex user requires a custom defined
permission `otx.user` (see the supplied config file).

Probably better off defining a role `otx.users` and adding required
rules to that role. YMMV.

