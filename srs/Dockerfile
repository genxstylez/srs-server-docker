FROM genxstylez/srs:2.0a3

ADD srs.conf /etc/srs.conf

CMD mkdir -p /data/log/ffmpeg && srs -c /etc/srs.conf

VOLUME ["/data"]
EXPOSE 1935
