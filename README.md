# KeySave
A Command Line Tool wich can save and load strings. Like a notepad, just more minialistic.

## Usage

```
savekey --save API_key IxDsLdj$2snLL&
```

This command would create a key called `API_key` and saves the Value `IxDsLdj$2snLL&` to it.
To access the key later, you should use this command:

```
savekey --load API_key
```

If you dont want to write `--save` or `--load`, then you can write `-s` or `-l`.

### Parameter List

| Short Parameter | Long Paramter | Function | Warnings |
|--|--|--|--|
| -? | --help     | Show a help like this |  |
| -v | --version  | Terminates the application after the Welcome-screen |  |
| -s | --save     | Saves the Key |  |
| -l | --load     | Loads a key |  |
| -d | --delete   | Deletes a key | - **NOT YET IMPLEMENTED** |
| -r | --reset    | Deletes any Key in the master.json file | - **NOT YET IMPLEMENTED** |
| -p | --password | Locks the -r Parameter with a password. | - **NOT YET IMPLEMENTED** <br/> - **PASSWORD SAVED IN PLAIN TEXT** |

## Warnings

- **KeySave has been developed on and for Linux. It has not been tested for Windows.**
- **KeySave stores the Values as a plain Text file (~/.savekey/master.json). It is not reccomendet to store verry private data with KeySave** 
