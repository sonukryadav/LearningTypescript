> To install the TypeScript compiler globally
> - npm i -g typescript

> To check if the installation is successful (it will return the version number if successful):
> - tsc -v

> To compile typescript code to javascript
> - tsc <fileName.ts>
>> If you want to specify the name of the output file:
>> - tsc <fileName.ts> --outfile <fileNameThatWeWantToKeep.js>

> To make TSC to compile code automatically
> - tsc <fileName.ts> -w

> How to Set Up the ts config File?
> - First, create the ts config file by running command:
>> - tsc --init
>>> - The ts config file should be in the root directory of your project