# Target-biased novel molecules Discovery:

RL_GraphVAE Driven Molecular Generation


sudo docker run --gpus all -d --rm -v $(pwd):/workspace -p 8500:8501 --name RL_GraphVAE ghcr.io/pip700/rl_graphvae:v2

http://0.0.0.0:8500/ via web-browser

for stoping;
sudo docker rm RL_GraphVAE --force
