# Trims The audio

### This module trims the audio you provide 

#### Make Sure That
- all files remain in the same directory
- there is a directory named `tmp` in the same directory 
- don't change file name except `index`
- you give buffer of the audio file


### USAGE

```javascript
const {mp3Cutter} = require('./index')
let buffer = await mp3Cutter(media, start, end);
```
<b>Note :</b>
- `media` Must be a Buffer 
- start values and end values are seconds and not any other format

 <b>This returns the audio as a buffer</b>
 
