Easy install and run any nodejs version on replit.com

## usage

1. fork this repl
2. change preferred nodejs version to install on `composer.json`
3. open shell then type `composer update`

now you can run `nodejs` and `npm` by typing `./vendor/bin/node` and `./vendor/bin/npm` also you can add to `PATH`, from secrets with adding key `PATH` and value `~/replname/vendor/bin:$PATH` (make sure to replace replname with your repl name).

demo express.js https://express.latihantik.repl.co

## links

repl: https://replit.com/@latihantik/express?v=1

github: https://github.com/cirebon-dev/replit_nodeinstaller

composer plugin: https://github.com/thecodingmachine/nodejs-installer