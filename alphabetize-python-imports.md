We should follow PEP-8 when organizing Python imports.

https://www.python.org/dev/peps/pep-0008/#imports

In addition, we should alphabetize Python imports for maximum readability and preventing duplicate imports:

https://stackoverflow.com/a/20763446/73056

When mixing and matching `import x` and `from y import z`, we should alphabetically sort by module name, ignoring the kind of import.

Here is an example:

```
import a_standard
import b_standard

import a_third_party
import b_third_party

import a_proprietary
from b_proprietary import g
from c_proprietary import d
import z_proprietary
```
