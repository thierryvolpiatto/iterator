iterator
========

Provide iterator functions for emacs


#Usage:

```emacs-lisp
(setq foo '(a b c d e))
(setq foo-iterator (iter-list foo))
(iter-next foo-iterator)
=>a
(iter-next foo-iterator)
=>b
(iter-next foo-iterator)
=>c
(iter-next foo-iterator)
=>d
(iter-next foo-iterator)
=>e
(iter-next foo-iterator)
=>nil
```

#Note:

Some of these features are inlined in [helm](https://github.com/emacs-helm/helm) and [ioccur](https://github.com/thierryvolpiatto/ioccur).
