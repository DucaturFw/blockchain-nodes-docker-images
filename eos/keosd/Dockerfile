FROM eosio/eos:v1.1.0

COPY config-jungle.ini /eos/data/config.ini
COPY genesis-jungle.json /opt/eosio/bin/genesis.json

ENTRYPOINT /opt/eosio/bin/keosd \
  --wallet-dir /eos/data \
  --data-dir /eos/data \
  --http-server-address=127.0.0.1:8900 \
  --http-alias=localhost:8900 \
  --http-alias=keosd:8900