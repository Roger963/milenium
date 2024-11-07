## Use odoo as parent image
ARG ODOO_VERSION=latest

FROM odoo:${ODOO_VERSION}
USER root

RUN pip3 install --ignore-installed pip --upgrade 



COPY ./odoo/resources/requirements.txt /tmp/

USER odoo