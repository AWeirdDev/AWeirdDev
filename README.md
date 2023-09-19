# im awd

Weekly bad meme

```python
import random
import string
from typing import overload

@overload
def find_friends(amount_or_name: int) -> list[str]: ...

@overload
def find_friends(amount_or_name: str) -> None: ...

def find_friends(amount_or_name: int | str):
    if isinstance(amount_or_name, str):
        return None
    else:
        return (
            "".join(random.sample(string.ascii_letters, 5))
            for _ in range(amount)
        )

friend = find_friends("myself")
print("got friend", friend)
```
