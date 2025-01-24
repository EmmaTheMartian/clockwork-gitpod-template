# Clockwork Gitpod Template

A template/reference repo containing a Gitpod configuration to automatically
install V and Clockwork.

## After Cloning This Template

- Update the `TODO` values in `v.mod`
- Add your project's name to `.gitignore`
- Replace this README

## Using the Template

You can either click the `Use this template` button at the top right to make a
new repo using this template, or you can run this in your shell:

```
git clone https://github.com/emmathemartian/clockwork-gitpod-template &&\
find clockwork-gitpod-template -maxdepth 1 -mindepth 1 -not -name .git -exec mv '{}' . \; &&\
rm -rf clockwork-gitpod-template
```

> This script will clone the template, then move all files from it into the
> working directory *except* for the `.git` folder, then finally delete the
> `clockwork-gitpod-template` folder.

## Template License

This template is licensed under MIT-0, which is MIT but no attribution needed.
Feel free to do whatever you want with this template, it took me literally 5
minutes to make :>

License text:

```
MIT No Attribution

Copyright 2025 EmmaTheMartian

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
