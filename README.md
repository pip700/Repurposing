# Repurposing
3D-VAE Driven Molecular Repurposing


sudo docker run --gpus all -d --rm -v $(pwd):/workspace -p 8502:8501 --name RL_GraphVAE ghcr.io/pip700/rl_graphvae:v1

http://http://0.0.0.0:8500/ via web-browser

for stoping;
sudo docker rm RL_GraphVAE --force
