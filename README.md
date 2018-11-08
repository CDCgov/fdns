# Foundation Services (FDNS)
This is a central repository with high level information on Foundation Services (FDNS), links to tutorials, example code, etc.

## What are Foundation Services?

Foundation Services (FDNS) is a library of foundational open source software components implemented as microservices. They can be assembled in various arrangements to rapidly and efficiently build modern, open, and interoperable public health software. They are considered “foundational” because of their high reusability and broad applicability to wide array of use cases.

## Why use Foundation Services?

FDNS are easily adapatable, portable, and open source. This can reduce costs and shorten schedules, allowing teams with limited resources to quickly build new applications or upgrade existing ones.

## Running Locally

### Before you start
For most repositories, you will need to have the following installed before getting up and running locally:

- Docker, [Installation guides](https://docs.docker.com/install/)
- Docker Compose, [Installation guides](https://docs.docker.com/compose/install/)
- **Windows Users**: This project uses `Make`, please see [Cygwin](http://www.cygwin.com/) for running commands in this README

## Packages and SDK's

Packages deployed to NPM:

* [FDNS JS SDK](https://www.npmjs.com/package/fdns-js-sdk)
* [FDNS React UI](https://www.npmjs.com/package/fdns-ui-react)

Other SDK's (more to come):

* [FDNS Java SDK](https://github.com/CDCgov/fdns-java-sdk)


## Example Apps

Example apps using the React UI and/or JS SDK:

* [Example HL7 Combiner Tool](https://github.com/CDCgov/ex-ui-hl7-combiner)

## Available Open Source Foundation Services

### Data Lake Services
* [FDNS Storage Microservice](https://github.com/CDCgov/fdns-ms-storage), the immutable storage layer for the Data Lake
* [FDNS Object Microservice](https://github.com/CDCgov/fdns-ms-object), a mutable layer for interacting with the Data Lake
* [FDNS Indexing Microservice](https://github.com/CDCgov/fdns-ms-indexing), the indexing or navigation layer of the Data Lake

### Other Utils
* [FDNS Gateway Microservice](https://github.com/CDCgov/fdns-ms-gateway), the gateway layer for connecting deployed microservices together
* [FDNS Combiner Microservice](https://github.com/CDCgov/fdns-ms-combiner), a microservice for combining JSON files into a single CSV or XLSX file
* [FDNS Business Rules Microservice](https://github.com/CDCgov/fdns-ms-rules), a microservice for ingesting and validating JSON files
* [FDNS Reporting Microservice](https://github.com/CDCgov/fdns-ms-reporting), a microservice for generating reports from the Data Lake in XML, JSON, CSV, or XLSX
* [FDNS CDA Utilities Microservice](https://github.com/CDCgov/fdns-ms-cda-utils), a microservice for parsing and generating CDA data
* [FDNS HL7 Utilities Microservice](https://github.com/CDCgov/fdns-ms-hl7-utils), a microservice for parsing, validating, and generating HL7 data
* [FDNS Microsoft Utilities Microservice](https://github.com/CDCgov/fdns-ms-msft-utils), a microservice for parsing Microsoft formatted documents

## Public Domain
This repository constitutes a work of the United States Government and is not
subject to domestic copyright protection under 17 USC § 105. This repository is in
the public domain within the United States, and copyright and related rights in
the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
All contributions to this repository will be released under the CC0 dedication. By
submitting a pull request you are agreeing to comply with this waiver of
copyright interest.

## License
The repository utilizes code licensed under the terms of the Apache Software
License and therefore is licensed under ASL v2 or later.

This source code in this repository is free: you can redistribute it and/or modify it under
the terms of the Apache Software License version 2, or (at your option) any
later version.

This soruce code in this repository is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE. See the Apache Software License for more details.

You should have received a copy of the Apache Software License along with this
program. If not, see http://www.apache.org/licenses/LICENSE-2.0.html

The source code forked from other open source projects will inherit its license.

## Privacy
This repository contains only non-sensitive, publicly available data and
information. All material and community participation is covered by the
Surveillance Platform [Disclaimer](https://github.com/CDCgov/template/blob/master/DISCLAIMER.md)
and [Code of Conduct](https://github.com/CDCgov/template/blob/master/code-of-conduct.md).
For more information about CDC's privacy policy, please visit [http://www.cdc.gov/privacy.html](http://www.cdc.gov/privacy.html).

## Contributing
Anyone is encouraged to contribute to the repository by [forking](https://help.github.com/articles/fork-a-repo)
and submitting a pull request. (If you are new to GitHub, you might start with a
[basic tutorial](https://help.github.com/articles/set-up-git).) By contributing
to this project, you grant a world-wide, royalty-free, perpetual, irrevocable,
non-exclusive, transferable license to all users under the terms of the
[Apache Software License v2](http://www.apache.org/licenses/LICENSE-2.0.html) or
later.

All comments, messages, pull requests, and other submissions received through
CDC including this GitHub page are subject to the [Presidential Records Act](http://www.archives.gov/about/laws/presidential-records.html)
and may be archived. Learn more at [http://www.cdc.gov/other/privacy.html](http://www.cdc.gov/other/privacy.html).

## Records
This repository is not a source of government records, but is a copy to increase
collaboration and collaborative potential. All government records will be
published through the [CDC web site](http://www.cdc.gov).

## Notices
Please refer to [CDC's Template Repository](https://github.com/CDCgov/template)
for more information about [contributing to this repository](https://github.com/CDCgov/template/blob/master/CONTRIBUTING.md),
[public domain notices and disclaimers](https://github.com/CDCgov/template/blob/master/DISCLAIMER.md),
and [code of conduct](https://github.com/CDCgov/template/blob/master/code-of-conduct.md).
