FROM langflowai/langflow-backend:latest
RUN mkdir /app/flows
COPY ./*json /app/flows/.
ENV LANGFLOW_LOAD_FLOWS_PATH=/app/flows
