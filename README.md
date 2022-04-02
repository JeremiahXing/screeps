# screeps
### this is code for screeps: world

##### too rollup your code from local to the    server you need one more step
create a new file named <strong>.sercet.json</strong> in the root and copy the code below
[you can get your screeps token here](https://screeps.com/a/#!/account/auth-tokens)
```json
{
    "main": {
        "token": "97d*****-****-****-****-**********86" /* fill in your screeps token */,
        "protocol": "https",
        "hostname": "screeps.com",
        "port": 443,
        "path": "/",
        "branch": "default"
    },
    "local": {
        "copyPath":"C:\\Users\\Username\\AppData\\Local\\Screeps\\scripts\\screeps.com\\default" /* the local code folder of your game*/
    }
}
```
<strong>this <i>.screct.json</i> file contains private field, please make sure add it to .gitignore if you want to upload your own code to github or else that in public</strong>

npm run bulid (generate main.js.map)


npm run push (submit code)


npm run local (submit code)
