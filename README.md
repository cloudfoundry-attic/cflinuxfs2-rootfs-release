### cflinuxfs2 rootfs BOSH Release

This bosh release contains the rootfs package as well as a job that will
extract the package to `/var/vcap/packages/cflinuxfs2/rootfs`.

#### Trusted certificates

Trusted certs can be installed in the rootfs by setting the
`rootfs_cflinuxfs2.trusted_certs` property to the certificate chain in any
order. For example:

TODO: add an example
```
```

#### Requirements

This release depends on recent bosh versions. In particular it requires
bosh-release version v206+ (1.3072.0) and stemcell version 3125+
