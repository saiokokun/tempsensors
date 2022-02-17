# Use the Nginx image
FROM nginx

# Remove the default nginc config file
RUN rm /etc/nginx/conf.d/default.conf

# Replace the config with out own
COPY nginx.conf /etc/nginx/conf.d/



