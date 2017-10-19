FROM armhf/alpine
LABEL maintainer "Peter Benjamin"
RUN apk --no-cache add \
	nmap \
	nmap-ncat \
	nmap-nping \
	nmap-nselibs \
	nmap-scripts
ENTRYPOINT [ "nmap" ]
