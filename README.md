# jsconsole
A javascript library that extends the native console to give the developer control over turning logs on and off in code

Add this script before all other scripts that use logs

## Usage Examples

### Disable/Enable all logs

console.active = false; //disable

console.active = true; //enable

### Disable/Enable some logs

console.doLog = false; //disable

console.doInfo = false; //disable

console.doLog = true; //enable

console.doInfo = true; //enable

### Log clearing

console.doClear; //console clearing code will no longer clear the console.
