FROM ubuntu:20.04
WORKDIR /app
COPY ./sample101.bmp ./sample101.bmp
COPY generate_samples.sh .
RUN chmod +x generate_samples.sh && ./generate_samples.sh
# EXPOSE 3000
CMD ["echo", "Application is ready!"]
