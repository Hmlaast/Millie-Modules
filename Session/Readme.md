# Writing Session to your Bots

This module provides a functionality to anyone who use Millie's QR to write session to your bot

``` javascript
const {MakeSession} = require('./session')

MakeSession(session_id,session_file)
```

this writes the session from the ```session_id``` to your ```session_file```

- Note that this method only works with the session you recieved from [here](https://millie-qr.herokuapp.com/)
