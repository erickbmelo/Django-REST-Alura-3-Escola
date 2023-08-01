Pro React subir, precisa adicionar essas linhas no package.json:  
    `"start": "react-scripts --openssl-legacy-provider start",`  
    `"build": "react-scripts --openssl-legacy-provider build",`

E no Windows, como admin:  
    `npm set strict-ssl false`