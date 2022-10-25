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

- **_NAV:** Documentation required for accurate coding was not available at the time of coding.
- **_INC:** Inconsistent with the available documentation.
- **_ILL:** The documentation used to code the episode was illegible, resulting in missing codes.
- **_LEX:** The code is present within the documentation, but written in a manner in which makes it impossible to code.

### Coding Errors

#### Basic Coding Errors

- **_OMI:** Code was not present in the coded episode.
- **_IRR:** Code is irrelevant to the coded episode.
- **_3RD:** Incorrect at the third character level.
- **_4RD:** Incorrect at the fourth character level.
- **_5TH:** Incorrect at the fifth character level.


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