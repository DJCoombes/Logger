# Logger

A simple C++ logging object, can be used to print messages to files or the console.

## Features

- Single easy to read header file.
- Very easy to use.

## Installation

Copy the header file into your include directory.

## Example usage

Here's an exaple of how the logger could be used.

```cpp
#include "logger.h"

int main() {
	LOG::Clear();

	LOG(DEBUG) << "Test";
	LOG(ERROR) << "2 + 3 = " << 2 + 3;

	return 0;
}
```

Here's what the console output looks like.

```bash
[DEBUG] Test
[ERROR] 2 + 3 = 5
```

And here's what the log file looks like.

```bash
[DEBUG] Test
[ERROR] 2 + 3 = 5
```
