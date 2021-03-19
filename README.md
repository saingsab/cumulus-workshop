# cumulus-workshop
My note of entire process of launching a relay chain, connecting parachains, transferring assets between chains, and developing parachain runtimes.

Clone Wroking and compartibility.

# Create the starting point that we will modify
polkadot build-spec --chain rococo-local --disable-default-bootnode > rococo-custom-plain.json

-- Alice KeyID


--chain rococo-custom.json \
--tmp \
--ws-port 9955 \
--port 30334 \
--bob \
--bootnodes /ip4/127.0.0.1/tcp/30333/p2p/PeerID


