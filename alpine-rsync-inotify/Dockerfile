# Use the latest Alpine Linux as the base
FROM alpine:latest

# Install rsync and inotify-tools (which provides inotifywait)
# We use --no-cache to keep the image small
RUN apk add --no-cache rsync inotify-tools bash sh

# Set a default command (can be overridden in Kubernetes)
CMD ["rsync", "--version"]