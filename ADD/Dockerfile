FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://docs.ansible.com/ansible/latest/collections/ansible/builtin/package_module.html /usr/share/nginx/html/index.html
CMD [ "nginx" , "-g", "daemon off;"]
