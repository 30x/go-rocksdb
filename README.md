# go-leveldb

This repository builds a Docker image that includes:

* golang (from the standard "Alpine" golang image)
* glide for dependency management
* LevelDB
* gcc so that images may be constructed that can compile "cgo" code and use LevelDB
