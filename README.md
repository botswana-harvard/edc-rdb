# edc-rdb

Link EDC to data in the RDB. The RDB has research data plus PIMS data.

* PIMS: Patient Information Management System for the Ministry of Health in Botswana
* RDB: "Research Database" where data is warehoused from the Botswana Combination Prevention Project (BCPP).

A subset of PIMS data, less PII, is batch loaded into the RDB. 

Current Objectives:
- verify data imported into the RDB against source data in the EDC;
- resolve ambiguous values reported in the EDC against a second source;
- manage a master patient list relative to EDC enrolled subjects;
- trace linkage-to-care flow by subject;
- support other QA efforts.
