## Besu IBFT2 Private Blockchain

**Prerequisite**
- Install docker compose

## To run
- Clone repo
- Go to `./genesis-generator`
- Make changes in `ibftConfigFile.json` as your preference
- Run `docker-compose up`. Genesis file and key pairs will be generated.
- Copy the `genesis file` to each node folder.
- Copy one key pair for each node and place it in the `data/`
- Run `docker-compose up -d` on root level of working directory.
- From the logs of bootnode (node-1) copy the enode url and add it to the `config.toml` for all other nodes.
-  **TO START** restart all the containers.
- For more details visit: https://medium.com/@prasanthvenugopalan_4575/creating-a-private-blockchain-using-hyperledger-besu-96c7f281bab4
