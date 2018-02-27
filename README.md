# cleverbot_luvit

``lit install Kogiku/cleverbot``

Usage example:
```lua
local cb = require('cleverbot')
local key = 'YOUR_API_KEY'

print(cb.talk('hello', key))
-- or
print(cb.talk('hello', key, false)) -- disable/clear conversation state
```
