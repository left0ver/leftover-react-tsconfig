# About 
这是我的关于react的tsconfig.json的配置

# Usage

```json

{
  "extends": "leftover-react-tsconfig",
  "compilerOptions": {
        //your config
  }
}

```

# 所有的配置项

```json 

{
  "compilerOptions": {
    "target": "es6",                                  
    "lib": ["dom", "dom.iterable", "esnext"],          
     "jsx": "react",                                
     "module": "esnext",                               
     "moduleResolution": "node",                       
     "resolveJsonModule": true,                       
     "allowJs": true,                                 
     "checkJs": true,                                  
     "declaration": true,                             
     "emitDeclarationOnly": true,                     
     "importHelpers": true,                            
     "downlevelIteration": true,                      
     "isolatedModules": true,                          
     "allowSyntheticDefaultImports": true,           
     "esModuleInterop": true,                             
     "forceConsistentCasingInFileNames": true,            
     "strict": true,                                      
     "exactOptionalPropertyTypes": true,               
     "noImplicitReturns": true,                        
     "noFallthroughCasesInSwitch": true,               
     "noImplicitOverride": true,                      
     "skipLibCheck": true                              
  }
}

```

# License

[MIT](https://github.com/left0ver/leftover-react-tsconfig/blob/main/LICENSE)
