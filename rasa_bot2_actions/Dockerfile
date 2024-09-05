
FROM rasa/rasa-sdk:3.6.2


WORKDIR /app

USER root


COPY ./actions /app/actions



RUN pip install --no-cache-dir rasa requests


EXPOSE 5055

# ENTRYPOINT ["rasa"]
# CMD ["run", "actions","--port","5055"]




