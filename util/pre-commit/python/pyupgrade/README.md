# pyupgrade pre-commit

"Upgrade" your Python code from old-style syntax to new. Examples:

```
dict([(a, b) for a, b in y])  # -> {a: b for a, b in y}
class C(object): pass         # -> class C: pass
from mock import patch        # -> from unittest.mock import patch
```
