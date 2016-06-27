# <%= moduleName %>
[![Build Status](https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>.svg?branch=master)](https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>)
[![Coverage Status](https://coveralls.io/repos/github/<%= githubUsername %>/<%= moduleName %>/badge.svg?branch=master)](https://coveralls.io/github/<%= githubUsername %>/<%= moduleName %>?branch=master)
[![Dependency Status](https://gemnasium.com/badges/github.com/<%= githubUsername %>/<%= moduleName %>.svg)](https://gemnasium.com/github.com/<%= githubUsername %>/<%= moduleName %>)
> <%- description %>

## Install
```
$ npm install --save <%= moduleName %>
```

## Now with update-notifier
The cli now uses [update-notifier][] to let the user know about updates to this program.

Users have the ability to opt-out of the update notifier by changing
the optOut property to true in ~/.config/configstore/update-notifier-rollodeqc-gh-user-streak.json.
The path is available in notifier.config.path.

Users can also opt-out by setting the environment variable NO_UPDATE_NOTIFIER
with any value or by using the --no-update-notifier flag on a per run basis.

## Usage
```js
const <%= camelModuleName %> = require('<%= moduleName %>')

<%= camelModuleName %>('unicorns')
//=> 'unicorns & rainbows'
```

## API
### <%= camelModuleName %>(input, [options])
#### input
Type: `string`

Lorem ipsum.

#### options
##### foo
Type: `boolean`<br>
Default: `false`

Lorem ipsum.<% if (cli) { %>

## CLI
```
$ npm install --global <%= moduleName %>
```

```
$ <%= moduleName %> --help

  Usage
    <%= moduleName %> [input]

  Options
    --foo  Lorem ipsum. [Default: false]

  Examples
    $ <%= moduleName %>
    unicorns & rainbows
    $ <%= moduleName %> ponies
    ponies & rainbows
```<% } %>


## License
AGPL-v3 © [<%- name %>](<%= website %>)
