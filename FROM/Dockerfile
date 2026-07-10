# FROM nginx:1.31.2-trixie-perl
# RUN echo "Hi GUys I am WOrking (RUN Command is working)" > /usr/share/nginx/html/index.html
# CMD ["nginx", "-g", "daemon off;"]
# COPY ./stocks.html /usr/share/nginx/html
# EXPOSE 80/tcp
# LABEL AUTHOR="Vinay" \
#     VERSION="v5" \
#     DATE="10-07-2026"

FROM nginx:1.31.2-trixie-perl
# WORKDIR /usr/share/nginx/html
# RUN touch workdirworking.txt
ADD https://raw.githubusercontent.com/daws-86s/notes/refs/heads/main/session-54.txt /usr/share/nginx/html/index.html
# RUN useradd vinay
# RUN chown -R vinay:vinay /usr/share/nginx
CMD ["nginx", "-g", "daemon off;"]
# USER vinay