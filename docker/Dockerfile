FROM linuxserver/ffmpeg:5.1.2

# Install mscore fonts
RUN apt-get update && \
    apt-get install -y fontconfig && \
    ( yes | apt-get install -y ttf-mscorefonts-installer ) && \
    fc-cache -f

