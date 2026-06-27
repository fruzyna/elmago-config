FROM python:3

RUN mkdir -p /config /output /opt
COPY ./zap2it-GuideScrape.py /opt

CMD python /opt/zap2it-GuideScrape.py -c /config/zap2itconfig.ini -o /output/xmltv.xml; sleep 86400
