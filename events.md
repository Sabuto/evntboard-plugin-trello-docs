# Events

### trello-plugin-load

This is fired when the plugin is first loaded

### trello-plugin-unload

This is fired when the plugin is unloaded

### trello-plugin-addCard

This will be fired when ```services.plugin('trello', 'addCard')``` is called, you will get an object with a key of response: with a value of 'Success' or 'Failed'
