# syntax=docker/dockerfile:1
ARG WEBUI_VERSION=main

FROM ghcr.io/open-webui/open-webui:${WEBUI_VERSION}

# Create data directory
RUN mkdir -p /app/backend/data

# Optional: Copy entrypoint script if needed
# COPY entrypoint.sh /usr/local/bin/entrypoint.sh
# RUN chmod +x /usr/local/bin/entrypoint.sh
# ENTRYPOINT ["/usr/local/bin/entrypoint.sh"]
