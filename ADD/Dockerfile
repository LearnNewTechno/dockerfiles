FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://docs.ansible.com/ansible/latest/collections/ansible/builtin/package_module.html /usr/share/nginx/html/index.html
RUN chmod +x /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp
CMD [ "nginx" , "-g", "daemon off;"]
