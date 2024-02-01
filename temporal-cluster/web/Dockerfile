FROM temporalio/web:1.22.4

ENTRYPOINT ["/bin/sh", "-c", "TEMPORAL_GRPC_ENDPOINT=$TEMPORAL_GRPC_HOST:7233 node server.js"]
