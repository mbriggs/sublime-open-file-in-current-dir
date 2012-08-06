```
   ____                      _______ __        ____         ______                           __     ____  _     
  / __ \____  ___  ____     / ____(_) /__     /  _/___     / ____/_  _______________  ____  / /_   / __ \(_)____
 / / / / __ \/ _ \/ __ \   / /_  / / / _ \    / // __ \   / /   / / / / ___/ ___/ _ \/ __ \/ __/  / / / / / ___/
/ /_/ / /_/ /  __/ / / /  / __/ / / /  __/  _/ // / / /  / /___/ /_/ / /  / /  /  __/ / / / /_   / /_/ / / /    
\____/ .___/\___/_/ /_/  /_/   /_/_/\___/  /___/_/ /_/   \____/\__,_/_/  /_/   \___/_/ /_/\__/  /_____/_/_/     
    /_/                                                                                                         
```

Quickly a file in the directory of the file you are looking at

## Usage

I use vintage, and this is the keymapping I use (note that I am overriding e,
but I don't use it anyways)

```javascript
  {
    "keys": ["e"],
    "command": "open_file_in_current_directory",
    "context": [{"key": "setting.command_mode"}]
  },
```
