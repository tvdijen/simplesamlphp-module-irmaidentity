FROM silintl/ssp-base
WORKDIR /data
COPY ../* /data/vendor/simplesamlphp/simplesamlphp/modules/IRMA-auth-source/
EXPOSE 80/tcp
ENTRYPOINT ["/usr/local/bin/s3-expand"]
CMD ["/data/run.sh"]
