FROM	tensin-base-ubuntu

RUN	apt-get update && apt-get install -y fuse && curl -sLo /opt/rclone.zip http://downloads.rclone.org/rclone-current-linux-amd64.zip && \
	unzip /opt/rclone.zip -d /opt/ && rm -f /opt/rclone.zip && \
	mv /opt/rclone-v*-linux-amd64/ /opt/rclone/ && \
	chmod 755 /opt/rclone/rclone && \
	ln -s /opt/rclone/rclone /usr/sbin/
