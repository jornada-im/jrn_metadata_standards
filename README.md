# jrn_metadata

**NOTE:** This repository has been merged with the jornada-im/documentation repository [here](https://github.com/jornada-im/documentation). It is now an archive only.

A repository of documents about best practices and standards for metadata creation at Jornada Basin LTER.

Please refer to these as you are packaging data and creating EML documents for Jornada Basin research products.

**Edit as you see fit, but please track your changes when possible and Greg will try to sync with the GitHub version of this repository.**

## Building the standards document

    pandoc JRN_metadata_standards.md --toc --metadata date="$(date +%Y-%m-%d%n)" -o ../JRN_metadata_standards.docx 
