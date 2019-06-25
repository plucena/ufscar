tokens

https://hyperledger-fabric.readthedocs.io/en/latest/token/FabToken.html#the-token-lifecycle



token issue --config /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/configorg1.json --mspPath /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/Admin@org1.example.com/msp --channel mychannel --type UFSCARCoin --quantity 10000 --recipient Org1MSP:/opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/User1@org1.example.com/msp



token list --config /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/configorg1.json --mspPath /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org1.example.com/users/User1@org1.example.com/msp --channel mychannel

token list --config /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/configorg1.json --mspPath /opt/gopath/src/github.com/hyperledger/fabric/peer/crypto/peerOrganizations/org2.example.com/users/User1@org2.example.com/msp --channel mychannel


