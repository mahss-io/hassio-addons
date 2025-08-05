ARG BUILD_FROM
FROM ghcr.io/moghtech/komodo-periphery:latest as original_periphery

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/usr/local/bin/periphery" ]