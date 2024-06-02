FROM fedora:latest

RUN dnf -y update && \
    dnf -y install @workstation-product-environment && \
    dnf clean all

CMD ["/usr/sbin/init"]
