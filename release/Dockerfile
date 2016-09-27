FROM aaronpederson/upstart

RUN ansible-galaxy install telusdigital.riofs
COPY playbook.yml /etc/
RUN ansible-playbook /etc/playbook.yml
