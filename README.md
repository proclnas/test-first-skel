Test First Skel
--

A simple skel with psr-4 autoload and phpunit/code coverage pre-configured

#### Creating a project with this skeleton:
```
$ composer create-project -sdev proclnas/test-first-skel project-name
```

So in the `project-name` folder the following structure we'll be created:
```
- project-name
  - src
  | ---- Your default namespace, which was generated dinamically with name: ProjectName
  - CHANGELOG.md
  | ---- Changelog to keep your updates and new features
  - composer.json
  | ---- A generic composer file with some basic configuration and namespace already configurated
  - phpunit.xml
  | ---- Phpunit configuration file, code coverage included
  - phpcs.xml
  | ---- Coding standard configuration, default: PSR-2 standards
  - README.md
  | ---- Some presentation about your new project :)
```

#### Pre configured composer commands

- Run phpunit test suit
    - `$ composer run-script test`
- Check for errors with phpcs based on PSR-2 standards
    - `$ composer run-script check`
- Fix issues found by phpcs using phpcbf
    - `$ composer run-script fix`

#### TODO
- Add docker-compose to easy app bootsrap (url rewrite etc)

#### License
```
MIT License

Copyright (c) 2019 Rodrigo Nas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
