# Jupy-Canvas

To start the entire application, first clone the repository:

```bash
git clone https://github.com/Jupyter-Canvas/jupy-canvas.git
```

Then, move to the root directory:

```bash
cd jupy-canvas
```

And build the docker compose:

```bash
docker-compose up --build
```

Or build it (for ARM-based processors like Apple Silicon M-Series) with a different file:

```bash
docker-compose -f docker-compose-arm.yml up --build
```

After everything is up and running, the application can be accessed on:

```bash
http://localhost:80
```

The directory 'Workspace' in this repository will be the entry point of the File Explorer. Feel free to include any files you want to work with in that directory.
