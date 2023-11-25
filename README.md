Easy install and run any nodejs version on replit.com

## Usage

1. create new repl and select import from github.

2. enter url https://github.com/cirebon-dev/replit_nodeinstaller

2. change preferred nodejs version to install on `composer.json`.

3. open shell then type `composer update`.

Now you can run `nodejs` and `npm` by typing `./vendor/bin/node` and `./vendor/bin/npm` also you can add to `PATH`, from secrets with adding key `PATH` and value `~/replname/vendor/bin:$PATH` (make sure to replace replname with your repl name).
