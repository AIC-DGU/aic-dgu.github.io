# aic-dgu.github.io

## How to run

1. Install `Docker` by following the official [instruction](https://docs.docker.com/get-docker/) per your OS.
2. Pull the official Docker Jekyll image <i>(once)</i>.
```bash
docker pull jekyll/jekyll
```
3. Pull the web source code <i>(once)</i>.
```bash
git clone https://github.com/AIC-DGU/aic-dgu.github.io
```

4. Move to the directory
```bash
cd aic-dgu.github.io
```

5. Run the docker jekyll image
```bash
docker run -it -v $(pwd):/srv -p 4000:4000 {jekyll image id pulled at the step 2} /bin/bash
```

6. On the docker container, run the command below
```bash
gem install jekyll
jekyll serve
```
