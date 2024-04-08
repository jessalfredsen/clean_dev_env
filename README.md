# clean_dev_env

A simple repo with a clean dev environment for Python projects.

## Usage

Edit `requirements.txt` to add the dependencies you need.

Run:

```bash
docker compose up --build
```

This will create a container with the dependencies installed and open a jupyter lab server. You can access it by opening the link in your browser. Likely at [http://localhost:8888](http://localhost:8888).

All files in the container are [mounted](docker-compose.yml) to the current directory. So you can edit files in your favorite editor and run them in the container.

Good luck!
