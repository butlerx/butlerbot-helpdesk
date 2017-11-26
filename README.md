# butlerbot-helpdesk

redbrick helpdesk plugin for butlerbot


## Install

```sh
yarn add butlerbot-helpdesk
```
Create a file in the plugin dir as follows

```js
import helpdesk from 'butlerbot-helpdesk';
export default helpdesk({
  development: {
    channels: ['#butlerbot'],
    channelsToExclude: [],
    channelsToJoin: ['#butlerbot'],
    },
    "commands": [
      "!cmt",
      "!helpdesk",
      "!chair",
      "!secretary",
      "!treasurer",
      "!pro",
      "!events",
      "!admins",
      "!webmaster",
      "!fyr",
      "!help"
    ],
    "pmCommands": [],
    "wiki": "http://wiki.redbrick.dcu.ie/mw/"
  },

  production: {
    channels: ['#butlerbot'],
    channelsToExclude: [],
    channelsToJoin: ['#butlerbot'],
    "commands": [
      "!cmt",
      "!helpdesk",
      "!chair",
      "!secretary",
      "!treasurer",
      "!pro",
      "!events",
      "!admins",
      "!webmaster",
      "!fyr",
      "!help"
    ],
    "pmCommands": [],
    "wiki": "http://wiki.redbrick.dcu.ie/mw/"
  },
});
```
