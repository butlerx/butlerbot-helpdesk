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
  },

  production: {
    channels: ['#butlerbot'],
    channelsToExclude: [],
    channelsToJoin: ['#butlerbot'],
  },
});
```
