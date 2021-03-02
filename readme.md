### SUCAT - Small Units of Change - Automated Tests
Not smart - we 'suck at' making cool acronyms...

- All progress (changes in the code) should be planned.
- devided into small units of change, preferably as small as meaningful and practically possible
- Each unit of change should bring the code back into a runnable state - not necessarily the entire code, but the parts close to the changes.
- Each unit of change in completed with a test of the changed code, and other code that comes in contact with it.
- Since we test so often, tests should be automated - otherwise you won't get it done, carefully enough.
- Well-defined, and well documented interfaces between methods not only reduce confusion, it forces you to think about data-structure and what parts of the code doe what, and why.
