FROM jborozdina/omnicored-docker

ADD omni-mainnet.conf /
ADD omni-testnet.conf /

ENTRYPOINT /usr/local/omnicore/src/omnicored \
  -conf=/${OMNI_CONFIG_NAME} \