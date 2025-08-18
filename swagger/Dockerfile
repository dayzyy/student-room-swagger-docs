# Base image that sets up Swagger UI to serve the API documentation
FROM swagger/swagger-ui

WORKDIR /usr/local/app/specs/

COPY . .

ENV SWAGGER_JSON=/usr/local/app/specs/openapi.yaml

EXPOSE 8080
