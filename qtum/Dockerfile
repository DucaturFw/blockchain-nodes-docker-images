FROM qtum/qtum:latest

ADD qtum-mainnet.conf /
ADD qtum-regtest.conf /
ADD qtum-testnet.conf /

ENTRYPOINT qtumd \
  -conf=/${QTUM_CONFIG_NAME} \
  -datadir=/qtum