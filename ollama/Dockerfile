# syntax=docker/dockerfile:1
ARG OLLAMA_VERSION

FROM ollama/ollama:${OLLAMA_VERSION}

# Create data directory
RUN mkdir -p /root/.ollama

# Optional: Copy entrypoint script if needed
# COPY entrypoint.sh /usr/local/bin/entrypoint.sh
# RUN chmod +x /usr/local/bin/entrypoint.sh
# ENTRYPOINT ["/usr/local/bin/entrypoint.sh"]
