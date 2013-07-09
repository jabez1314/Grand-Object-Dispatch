# Grand Object Dispatch

Objective-C wrapper for Grand Central Dispatch with method for every single dispatch call and with some useful additions.

## Additions

  - **Detection of _Current Queue_** using `dispatch_get_specific`.
  - **Deadlock-safe** `-sync:` method.
  - Convenience initializer for reverse-DNS label.
  - Accessors for _Main Queue_ and _Global Concurrent Queues_.
  - Method `-log:` which is replacement for deprecated `dispacth_debug`.
  - Better macro for `dispatch_once`.

### Implemented (or not yet)

  - [Dispatch Queues][1]
  - Dispatch Groups
  - Dispatch Semaphores
  - Dispatch Sources
  - Dispatch IO
  - Dispatch Data


---
_Version 0.1.0_

MIT License, Copyright © 2013 Martin Kiss

`THE SOFTWARE IS PROVIDED "AS IS", and so on...` see [`LICENSE.md`][7] for more.

[1]: Sources/GODQueue.h
[7]: LICENSE.md