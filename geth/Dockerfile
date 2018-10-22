FROM ethereum/client-go:stable

ENTRYPOINT geth \
  ${GETH_NETWORK} \
  --datadir=/geth \
  --syncmode=${GETH_SYNCMODE} \
  --port=${GETH_P2P_PORT} \
  --rpc \
  --rpcaddr=${GETH_RPC_ADDR} \
  --rpcport=${GETH_RPC_PORT} \
  --rpcapi=${GETH_RPC_INTERFACES} \
  --ipcdisable \
  --cache=1024 \
  --nousb
