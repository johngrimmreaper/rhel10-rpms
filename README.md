# rhel10-rpms

Public generated **stable RHEL 10 RPM repository**.

Paired private build-control repository: `johngrimmreaper/rhel10-rpm-packaging`.

The `main` branch contains only repository documentation. Published RPMs,
SRPMs, signed `repodata/`, repository descriptors, the public signing key,
generated provenance and the static package browser are generated onto the
`gh-pages` deployment branch by `rpm-builder`.

This repository starts fresh as part of the paired-repository migration; legacy
RPM binaries from `johngrimmreaper/rpm-packages` are intentionally not copied.
The published state is disposable/rebuildable from the private controller.

Expected Pages URL after first publication:

`https://johngrimmreaper.github.io/rhel10-rpms/`
