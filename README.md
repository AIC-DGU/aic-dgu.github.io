# aic-dgu.github.io

![Beautiful Jekyll CI](https://github.com/AIC-DGU/aic-dgu.github.io/workflows/Beautiful%20Jekyll%20CI/badge.svg)

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
(Linux) docker run -it -v $(pwd):/srv -p 4000:4000 {jekyll image id pulled at the step 2} /bin/bash
(Windows10)  docker run -it -v {Absolute Path}:/srv -p 4000:4000 {jekyll image id} /bin/bash
  On Windows10, Running this code on CMD is recommended.
  To set up Absolute Path, you may want to go to settings on Docker.
  "Absolute Path" means the directory you clone this project
```
6. On the docker container, run the command below
```bash
gem install jekyll
jekyll serve
```
