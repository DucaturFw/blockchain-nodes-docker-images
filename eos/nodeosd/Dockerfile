FROM eosio/eos:v1.1.0

COPY config-jungle.ini /config.ini
COPY genesis-jungle.json /opt/eosio/bin/genesis.json

ENTRYPOINT /opt/eosio/bin/nodeosd.sh \
  --genesis-json genesis.json \
  --max-transaction-time=1000 \
  --data-dir /eos/data \
  -e