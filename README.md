glip
====

Code checker and git hook.

To use as git hook: 

    $ cat > .git/hooks/pre-commit
    #!/bin/sh
    <path-to>/glip -c <path-to>/glip-hook.cfg
    <ctrl-D>
    $ chmod -x .git/hooks/pre-commit

See inline doc in glip/glip-hook.cfg
