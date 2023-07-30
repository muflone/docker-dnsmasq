FROM archlinux:base

# Install packages
RUN pacman -Syu --noconfirm dnsmasq

# Define exposed ports
EXPOSE 53/udp

# Define starting command
ENTRYPOINT ["/usr/bin/dnsmasq"]
CMD ["--keep-in-foreground"]

