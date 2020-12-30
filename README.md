# Business Jekyll Theme

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


Business Jekyll Theme is a theme that is designed to be used for small and medium business. It is designed by a team from [Technext](https://github.com/technext/). The theme is then ported over by [Melvin Ch'ng](http://melvinchng.github.io) for Jekyll support. The original source code can be obainted from Technext's [repository](https://github.com/technext/office)

Unlike most Jekyll Themes, Business Jekyll Theme is not meant to be a single page theme. This theme is a package that you can use for your business website or promote certain project. I reorganized all the files and make it Jekyll friendly.

Big thanks to the creator of Office as this theme would not be possible without their hard work! You are always welcome to contribute to this repository to make it better!

**Example Site**
- [Business Jekyll Theme](https://business-jekyll-theme.github.io)

**Example Site From The Original Creator**
- [Office Template](http://demo.themewagon.com/preview/office-responsive-multipage-bootstrap-template)

## Feature
- Responsive layout
- CSS Framework - Bootstrap 3
- Beautiful icons by Fontawesome
- Clean, simple and elegant
- Multi page Template
- Well commented and structured coding
- Easy to use
- It's Free!

## Note
I removed certain features from the original theme packages as we do not really need it. I modified the original source code slightly to make it more mobile friendly and reusable. 

## Installation
1. For first time user, you have to install Ruby and Rails. If you do not have Ruby on Rails installed, you may follow [this tutorial](http://melvinchng.github.io/rails/RubyOnRailsInstallation.html) that I wrote for Windows, Linux, and MacOS (installation videos are included).
2. Install Jekyll by using the command `gem install jekyll`.
3. Start your localhost server by using the command `jekyll serve`. Make sure that you are at the root directory of your folder before using this command.
4. Your site should be accessible at `localhost:4000`.
5. For additional information about Jekyll, refer to the [official website](http://jekyllrb.com/). 

## Enjoy!
