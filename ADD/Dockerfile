FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
Add https://raw.githubusercontent.com/joindevops1/ansible/main/01-playbook.yaml /usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]