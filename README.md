# code-genie-cli

## Description
- This Repository For Code Genie Sample Files, Directory Generate

### For USER
>1. you must install the @unvus/code-genie
>2. You need to go to the <b>top of your project module directory.</b>
>3. And use Command Line ``codegenie init``
>4. The final step is to edit the created files!

### Command Line
```bash
cd {Your Modules Directory}

npm i -g @unvus/code-genie

codegenie init
```

### For Developer
#### 2024.05.08 Fixed ...

### For Manual Update
>1. You can Use Files -> ``init.js`` and ``package.json``
>> * If you Fix Files. You Must be fix <b>Version</b> in ``package.json``<br>
>> -> ex) "version": "0.0.1" to "version": "0.0.2" <br><br>
>> Or Using CLI Commands in Root Directory -> ``npm version patch`` || ``npm version minor`` || ``npm version major`` <br>
>> -> This Command Will Update Version Automatically For Update.