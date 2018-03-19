# Overview

The purpose of the Shift/Pedalpalooza Calendar is to empower citizens to create and view bike events and to spread bike fun.

# Software

built using:
- node
- docker
- [hugo v0.30.2](https://gohugo.io) 
- && the theme ["learn"](https://learn.netlify.com)
- && the content from [the legacy shift website](https://shift2bikes.org)
- && [Netlify web hosting](https://www.netlify.com) to serve the content

You can browse the current state here:  https://docs.shift2bikes.org

## Contributing

- If you want to change something about the site configuration or theme, [pull requests](https://help.github.com/articles/creating-a-pull-request/) are welcome.  Once you create a PR, you can immediately check out [a link to the build status and log and a preview of your changes](https://app.netlify.com/sites/shift-docs/deploys)
- If you only want to edit content (including creating new docs), [visit the CMS here](https://docs.shift2bikes.org/admin/#) and sign up - then you can edit it in your browser similar to wordpress.

## Local development
1. install docker
2. clone repo: `git clone https://github.com/sdobz/shift-docs.git`
3. clone submodules `git submodule update --init --recursive`
4. start shift site `./shift up`
5. visit `https://localhost:4443/`


## Netlify deployment
1. [fork repo](https://help.github.com/articles/fork-a-repo/)
2. [deploy on Netlify](https://app.netlify.com/start) by linking your forked repo.  Included configuration file `netlify.toml` should mean 0 configuration required to get the site running (though the CMS will not work without some [additional configuration](https://www.netlifycms.org/docs/quick-start/#authentication))

# License

This repository is under MIT License:

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.