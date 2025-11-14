FROM ubuntu:latest

RUN apt update && apt upgrade -y && \
    apt install -y postfix dovecot-core dovecot-imapd dovecot-pop3d iputils-ping  net-tools nano vim

COPY main.cf /etc/postfix

EXPOSE 25 587 143 993 110 995

CMD service postfix start && service dovecot start && tail -F /var/log/mail.log