# streamlit-docker

## cmd
`streamlit run app.py` <br>
`docker build -f Dockerfile -t app:latest .` <br>
`docker run -p 8501:8501 app:latest` <br>

### interactive mode
`docker run -itd [docker_image] /bin/bash` <br>
`docker exec -it [container_id] bash #by ID ` <br>

## credits
https://maelfabien.github.io/project/Streamlit/#dockerfile <br>
