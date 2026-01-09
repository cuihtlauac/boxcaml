535c466c935bb7076ff517e425cd08f8b2f6a356

Command: `sudo apt-get update`
Status: SUCCESS
Command: `sudo apt-get install --no-install-recommends -y rsync opam`
Status: SUCCESS
Command: `opam init --bare --disable-sandboxing -y`
Status: SUCCESS
Command: `opam switch create 5.2.0+ox --repos ox=git+https://github.com/oxcaml/opam-repository.git,default -y`
Status: SUCCESS
Command: `opam install -y ocamlformat`
Status: SUCCESS

Command: `opam install -y merlin`
Status: SUCCESS

Command: `opam install -y ocaml-lsp-server`
Status: SUCCESS

Command: `opam install -y utop`
Status: SUCCESS

Command: `opam install -y parallel`
Status: SUCCESS

Command: `opam install -y core_unix`
Status: SUCCESS

