# voyager-tagtables
Voyager tag tables modified for use by the UCLA Libraries.

Includes only the Oclc tag tables used by UCLA, not the Marc21 or Rlin tables also distributed with Voyager, which UCLA does not use.

Also includes "MARC21 Repertoire.cfg", which UCLA has changed to add support for some characters which are not supported in MARC21 MARC-8 encoding.

Create archive file for deployment staff:
```
$ zip -r -9 tag_tables_20170717.zip * -x README.md
```
changing YYYYMMDD as needed.

