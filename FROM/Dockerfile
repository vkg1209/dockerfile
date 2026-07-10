FROM nginx:1.31.2-trixie-perl
RUN echo "Hi GUys I am WOrking (RUN Command is working)" > /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
COPY ./stocks.html /usr/share/nginx/html
EXPOSE 80/tcp
LABEL AUTHOR="Vinay" \
    VERSION="v5" \
    DATE="10-07-2026"
