This repository provides code to setup GCP Landing Zone in an organisation. 

You need to start from the repo below in the order specified.

```code
 manual + automated               automated
+--------------------+           +----------------------+
|                    |           |                      |
|  gpc-lz-bootstrap  +---------->|  gcp-lz-foundations  |
|                    |           |                      |
+--------------------+           +----------------------+
          ^                                 ^
          |                                 |
          |                                 |
          |                      +----------+-----------+
          |                      |                      |
          +----------------------+  gcp-lz-products     |
                                 |                      |
                                 +----------------------+
                                            ^
                                            |
                                            |
                                 +----------+-----------+
                                 |                      |
                                 |  gcp-lz-modules      |
                                 |                      |
                                 +----------------------+
```

1. [gcp-lz-bootstrap](https://github.com/XBankGCPOrg/gcp-lz-bootstrap)
2. [gcp-lz-foundations](https://github.com/XBankGCPOrg/gcp-lz-foundations)
3. [gcp-lz-products](https://github.com/XBankGCPOrg/gcp-lz-products) (if updating products)
4. [gcp-lz-modules](https://github.com/XBankGCPOrg/gcp-lz-modules) (if updating modules)

