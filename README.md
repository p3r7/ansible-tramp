# ansible-tramp

Helper functions to retrieve an Ansible inventory as an elisp object.

Helm binding to connect to any host from the inventory.


## Installation

Not yet on [Melpa](https://melpa.org/).

For now, the recommended way to install is with [use-package](https://github.com/jwiegley/use-package), [quelpa](https://github.com/quelpa/quelpa) and [quelpa-use-package](https://github.com/quelpa/quelpa-use-package).

To require everything:

```el
(use-package ansible-tramp
  :quelpa (ansible-tramp :fetcher github :repo "p3r7/ansible-tramp"))
```
