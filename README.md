# tts-webui

docker build -t local/rvc-webui:latest "<https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI.git#main>"

docker compose up -d

docker logs -f rvc-webui
docker logs -f tts-webui
