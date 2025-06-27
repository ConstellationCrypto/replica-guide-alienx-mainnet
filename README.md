# Running a Replica node

This repo is setup to easily run alienx replica nodes. Simply run `docker-compose up` to bring a replica node up locally.

The docker image for alienx is hosted in a public docker repo: `offchainlabs/nitro-node:v3.5.2-33d30c0`

The nodeConfig file is prepopulated with alienx parameters. The current setup uses a public rpc url for the Ethereum mainnet rpc and stores node data in docker volume.
