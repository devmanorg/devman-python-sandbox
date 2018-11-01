FROM ubuntu:18.04
RUN mkdir /app
COPY gotty /app
COPY index.html /app
RUN chmod +x /app/gotty
RUN apt-get update && apt-get install -y \
            vim \
            git \
            nano \
            python3.6 \
            locales
RUN useradd -d /home/devman -m -s /bin/bash devman
RUN ln -s /usr/bin/python3.6 /usr/bin/python
RUN locale-gen en_US.UTF-8
ENV LANG en_US.UTF-8  
ENV LANGUAGE en_US:en  
ENV LC_ALL en_US.UTF-8 
ENV TERM xterm-256color
RUN echo shopt -s histappend >> /home/devman/.bashrc
ENV PROMPT_COMMAND history -a;$PROMPT_COMMAND
USER devman
WORKDIR /home/devman
EXPOSE 8081
CMD ["/app/gotty", "--permit-write", "--reconnect", "--port", "8081", "--index", "/app/index.html", "/bin/bash"]

