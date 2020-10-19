docker build -t heathrobertson/nix:latest .

docker run -it \
--name nix-python \
-v $(pwd):/home/ci  \
heathrobertson/nix


#CMD ["nix-shell", "--command", "jupyter lab --allow-root --no-browser --ip=0.0.0.0 --port=8888"]

