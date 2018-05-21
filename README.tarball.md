Packaging a tarball from git
==============================

After releasing, please generate a tarball:

  $ VERSION=FIXME

  $ git archive --format=tar --prefix=dokuwiki-${VERSION}/ ${VERSION} | gzip -n -9 > dokuwiki-${VERSION}.tar.gz

