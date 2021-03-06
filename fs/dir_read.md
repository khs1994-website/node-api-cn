<!-- YAML
added: v12.12.0
-->

* Returns: {Promise} containing {fs.Dirent|null}

Asynchronously read the next directory entry via readdir(3) as an
[`fs.Dirent`][].

After the read is completed, a `Promise` is returned that will be resolved with
an [`fs.Dirent`][], or `null` if there are no more directory entries to read.

_Directory entries returned by this function are in no particular order as
provided by the operating system's underlying directory mechanisms._

