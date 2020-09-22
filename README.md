# ARF - Assembler Repository Function #

**Assembler**, receives a request, asks the Repository layer for logical models, passes these to the Function layer, assembles and returns the result.

**Repository**, receives requests from the Assembler layer, returns logical models built from datastores.

**Function**, receives requests and logical models from the Assembler layer, returns the results of an idempotent operation.

---

Nathan Barlow & James Orson, 9/21/2020
