# micerocker 0.1.2

* Declares `mice` as `Depends` so that internal datasets will be findable
* Sets minimum `mice` version to 3.16.4, specifies remotes for `mice`
* Repairs an error in the logic of `get_data_uploads()`

# micerocker 0.1.1

* Exports all end point handler
* Adds `data_uploads` argument to `mice_longfmt_handler()`
* Replaces the role of the global R variables `data_uploads` by the environmental variable `MICEREST_DATA_UPLOADS`

# micerocker 0.1.0

* Selects files `webmice_function.R` and `webmice_handlers.R` from `amices/webmice`
* Declares dependencies
* Documents function arguments
* Runs styler and linter to improves consistency
* Creates initial package `micerest`
