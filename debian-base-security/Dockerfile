FROM dopetik/debian-base-standard

COPY setup/ /usr/local/debian-base-setup/
RUN /usr/local/debian-base-setup/030-debian-base-security

CMD ["/usr/local/bin/boot-debian-base"]

