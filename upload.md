cl run valid_image_paths.csv:valid_image_paths.csv MURA-v1.1:valid MURA:MURA "python3 MURA/main.py valid_image_paths.csv predictions.csv" -n run-predictions --request-cpus 4 --request-memory 32g --request-docker-image sqpeng1996/mura2:v5