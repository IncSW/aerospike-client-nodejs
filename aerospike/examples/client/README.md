# Examples 

## Setup

In order to run the examples you should first run:

		$ sudo npm link aerospike

This will resolve the dependecies needed for the examples.

## Usage

You can simply run each example independently:

		$ node <example>

Most of these examples require a key to act upon, and 
can optionally take a hostname, port, and namespace of the
cluster. The default server is on 127.0.0.1 at port 3000 
(a local server installation).

Each example provides usage information via a `--help` flag:

		$ node <example> --help

The following are the included examples:

- Basic Operations
	- exists.js - check the existence of a record.
	- get.js - read a record.
	- select.js - read specific bins of a record.
	- put.js - write a record.
	- remove.js - remove a record.
	- operate.js - perform multiple operations on a record.
	- info.js - get cluster state information.
- Batch Operations
	- batch_exists.js – check the existence of a batch of records.
	- batch_get.js - read a batch of records.
- Range Operations
	- range_get – read a range of records.
	- range_put – write a range of records.
	- range_remove – remove a range of records.
	- range_validate – write and validate a range of records.
