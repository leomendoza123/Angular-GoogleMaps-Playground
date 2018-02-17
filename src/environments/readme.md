

#### To build this environment files I am using dotenv and scripts 

See more at: 

 https://medium.com/@natchiketa/angular-cli-and-os-environment-variables-4cfa3b849659

 https://github.com/natchiketa/angular-cli-envvars


To create generate this environment files create a '.env' file at the root of the project containing the required variables:

example: 

```
googleMapKey=123123123123123123123
```

Then run **'npm start'** to generate dev mode or **'npm run-script build'** for prod mode 