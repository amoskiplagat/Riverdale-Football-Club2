# Use lightweight nginx image
FROM nginx:alpine

# Set maintainer (optional good practice)
LABEL maintainer="Riverdale FC <info@riverdalefc.com>"

# Copy site files into the nginx html folder
COPY . /usr/share/nginx/html

# Expose port 80
EXPOSE 80

# Healthcheck to ensure nginx is responding
HEALTHCHECK --interval=30s --timeout=5s --retries=3 CMD wget -qO- http://localhost:80 || exit 1
