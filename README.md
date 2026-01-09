Fri Jan  9 11:55:10 UTC 2026

535c466c935bb7076ff517e425cd08f8b2f6a356

✅ Success

`sudo apt-get update`
✅

`sudo apt-get install --no-install-recommends -y rsync opam`
✅

`opam init --bare --disable-sandboxing -y`
✅

`opam switch create 5.2.0+ox --repos ox=git+https://github.com/oxcaml/opam-repository.git,default -y`
✅

`opam install -y ocamlformat`
✅

`opam install -y merlin`
✅

`opam install -y ocaml-lsp-server`
✅

`opam install -y utop`
✅

`opam install -y parallel`
✅

`opam install -y core_unix`
✅

