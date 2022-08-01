# Targets that compile

**Note: this list isn't up to date.**

This is an auto-generated table showing which binaries compile for each target-triple. Note that this **does not** indicate that they are fully implemented, or that the tests pass.

|######OS######|###ARCH####|arch|base32|base64|basename|cat|chgrp|chmod|chown|chroot|cksum|comm|cp|csplit|cut|date|df|dircolors|dirname|du|echo|env|expand|expr|factor|false|fmt|fold|groups|hashsum|head|hostid|hostname|id|install|join|kill|link|ln|logname|ls|mkdir|mkfifo|mknod|mktemp|more|mv|nice|nl|nohup|nproc|numfmt|od|paste|pathchk|pinky|printenv|printf|ptx|pwd|readlink|realpath|relpath|rm|rmdir|seq|shred|shuf|sleep|sort|split|stat|stdbuf|sum|sync|tac|tail|tee|test|timeout|touch|tr|true|truncate|tsort|tty|uname|unexpand|uniq|unlink|uptime|users|wc|who|whoami|yes|
|--------------|-----------|----|------|------|--------|---|-----|-----|-----|------|-----|----|--|------|---|----|--|---------|-------|--|----|---|------|----|------|-----|---|----|------|-------|----|------|--------|--|-------|----|----|----|--|-------|--|-----|------|-----|------|----|--|----|--|-----|-----|------|--|-----|-------|-----|--------|------|---|---|--------|--------|-------|--|-----|---|-----|----|-----|----|-----|----|------|---|----|---|----|---|----|-------|-----|--|----|--------|-----|---|-----|--------|----|------|------|-----|--|---|------|---|
|linux-gnu|aarch64|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|linux-gnu|i686|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|linux-gnu|powerpc64|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|linux-gnu|riscv64gc| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
|linux-gnu|x86_64|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|windows-msvc|aarch64|y|y|y|y|y| | | | |y|y|y|y|y|y|y|y|y| |y|y|y| |y|y|y|y| |y|y|y|y| | |y| |y|y|y| |y| | |y|y|y| |y| |y|y|y|y| | |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| | |y|y|y|y|y|y| |y|y|y|y|y| |y|y|y| |y| |y| | |y|
|windows-gnu|i686|y|y|y|y|y| | | | |y|y|y|y|y|y|y|y|y| |y|y|y| |y|y|y|y| |y|y|y|y| | |y| |y|y|y|y|y| | |y|y|y| |y| |y|y|y|y| | |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| | |y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y| |y| |y| |y|y|
|windows-msvc|i686|y|y|y|y|y| | | | |y|y|y|y|y|y|y|y|y| |y|y|y| |y|y|y|y| |y|y|y|y| | |y| |y|y|y|y|y| | |y|y|y| |y| |y|y|y|y| | |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| | |y|y|y|y|y|y| |y|y|y|y|y| |y|y|y| |y| |y| |y|y|
|windows-gnu|x86_64|y|y|y|y|y| | | | |y|y|y|y|y|y|y|y|y| |y|y|y| |y|y|y|y| |y|y|y|y| | |y| |y|y|y|y|y| | |y|y|y| |y| |y|y|y|y| | |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| | |y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y| |y| |y| |y|y|
|windows-msvc|x86_64|y|y|y|y|y| | | | |y|y|y|y|y|y|y|y|y| |y|y|y| |y|y|y|y| |y|y|y|y| | |y| |y|y|y|y|y| | |y|y|y| |y| |y|y|y|y| | |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| | |y|y|y|y|y|y| |y|y|y|y|y| |y|y|y| |y| |y| |y|y|
|apple MacOS|aarch64|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|apple MacOS|x86_64|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|freebsd|x86_64|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|
|netbsd|x86_64|y|y|y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y| |y|y| |y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y| | |y| |y|y|
|android|aarch64|y|y|y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y| |y|y| |y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y| |y|y|y|y| |y|y|y|y|y|y| |y|y|y| | |y| |y|y|
|android|x86_64|y|y|y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y| |y|y|y|y|y|y|y|y|y| |y|y| |y|y|y|y|y|y|y|y|y|y|y|y| |y|y|y|y|y| |y|y|y|y|y|y|y|y|y|y|y|y|y|y|y| |y|y| |y|y|y|y| |y|y|y|y|y|y| |y|y|y| | |y| |y|y|
|solaris|x86_64| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
|wasi|wasm32| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
|redox|x86_64| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
|fuchsia|aarch64| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |
|fuchsia|x86_64| | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |