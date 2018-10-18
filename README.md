# pg_statsinfo 3.3.0 with a patch for debian-based systems

## About this

This repository provides a patched version of pg_statsinfo 3.3.0 for debian-based systems (like Docker's `postgres` image.).

Due to upstream issue, `pg_config` in Debian package reports wrong LIBDIR for `libpgcommon`, `libpgport`,
thus failing build of pg_statsinfo.

c.f. https://github.com/reorg/pg_repack/issues/179
