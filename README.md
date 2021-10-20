# streamlit-docker

## cmd
### startup
`streamlit run app.py` <br>
`docker build -f Dockerfile -t app:latest .` <br>
`docker run -p 8501:8501 app:latest` <br>

### interactive mode
`docker run --gpus all -itd [docker_image] /bin/bash` <br>
`docker exec -it [container_id] bash #by ID ` <br>
`cd mnt/c/` <br>

### copy files
`docker cp container_id:/foo.txt foo.txt` <br>

### notes
CUDA toolkit is for compiling CUDA application on WSL 2 <br>
WSL 2 GPU Paravirtualization no need for NVIDIA Container Toolkit <br>

## credits
https://maelfabien.github.io/project/Streamlit/#dockerfile <br>
https://docs.nvidia.com/cuda/wsl-user-guide/index.html#ch02-sub03-installing-wsl2 <br>
https://blog.roboflow.com/use-the-gpu-in-docker/ <br>
