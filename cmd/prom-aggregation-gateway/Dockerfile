FROM alpine:3.10
COPY prom-aggregation-gateway /
WORKDIR /
# Inform Docker that the container is listening on the specified port at runtime.
EXPOSE 9091
# Run the specified command within the container.
CMD [ "./prom-aggregation-gateway" ]
