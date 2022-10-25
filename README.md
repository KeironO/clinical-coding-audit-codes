# Free and Open Source Audit Codes for Clinical Coding

A bunch of free and open source audit codes for use in auditing both manual and automated clinical coding. Sister project to CLIVSECO.


## Terminology

This dictionary uses 5 major 'types' of codes:

- PD - Primary Diagnosis
- SD - Secondary Diagnosis
- EX - External Cause (specific to just external cause errors)
- PP - Primary Procedure
- SP - Secondary Procedure

So **_NAV** will become  **PDNAV**...

### Documentation Issues

Documentation issues describe issues that are caused wholly or in part by discrepancies within the clinical documentation used to code a given episode. 

- **_NAV:** Documentation required for accurate coding was not available at the time of coding.

> **Example:** The base documentation states that they are awaiting histological/pathological report, and it is later found on the Welsh Clinical Portal and has not been coded.

- **_INC:** Inconsistent with the available documentation.

> **Example:** Documentation has noted that the patient has tested negative for HPV, but the coder has entered a B977 code in place. 

- **_ILL:** The documentation used to code the episode was illegible, resulting in missing codes.

> **Example:** The coder has failed to pick up something from the case documentation due to it being illegible.

- **_LEX:** The code is present within the documentation, but written in a manner in which makes it impossible to code.

> **Example:** The author of the case documentation has used incorrect or informal terminology to describe a clinical outcome.

### Coding Errors

Coding Errors are self descriptive.

#### Basic Coding Errors

- **_OMI:** Code was not present in the coded episode.

> **Example:** The code is clearly present in the documentation and has not been coded.

- **_IRR:** Code is irrelevant to the coded episode.

> **Example:** The code is completely irrelevant to the coded episode and does not reflect anything withing the source documentation.

- **_3RD:** Incorrect at the third character level.

> **Example:** The code is correct up until the third character where an error has been made in the subdivision. For example Hypertension might have accidentally been coded as I11X instead of I10X.

- **_4TH:** Incorrect at the fourth character level.

> **Example:** The code is correct up until the fourth character where an error has been made in the subdivision.

- **_5TH:** Incorrect at the fifth character level.

> **Example:** The code is correct up until the fifth character where an error has been made in the final subdivision.


#### External Cause Codes

- **EXTER:** External cause code has been termed incorrectly.
- **EXMAP:** External cause code has been mapped incorrectly.
- **EXOMI:** External cause code was not present in the coded episode.
- **EXINC:** External cause code is incorrect.
- **EXIRR:** External cause code is irrelevant.


### Misc

- **CLIFA:** Issue with the auto coder at the time of automated coding.
- **DWARE:** Issues with the data warehouse at the time of automated coding.
- **CONSU:**: Consultant has requested specific coding.
- **SNOMM:** Terminology missing from SNOMED-CT.


## License

This project is proudly licensed under the terms of the permissive MIT License.

Copyright 2022 Keiron O'Shea

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.