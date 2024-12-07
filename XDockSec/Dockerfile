FROM ubuntu:latest

RUN apt-get update && \
    apt-get install -y \
    gnome-system-monitor \
    xauth \
    x11-apps \
    dbus-x11 \
    && rm -rf /var/lib/apt/lists/*

ENV DISPLAY=host.docker.internal:0

CMD ["gnome-system-monitor"]