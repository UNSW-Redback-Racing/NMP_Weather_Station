FROM nginx:alpine

COPY nginx.conf /etc/nginx/nginx.conf

# Remove default nginx index page
RUN rm -rf /usr/share/nginx/html/*

# Copy from the stahg 1
COPY build /usr/share/nginx/html

EXPOSE 80