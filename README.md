# electron-vite-react-serialport

a simple application to test the successful packaging of serialport within a electron react-based application

```sh
# clone the project
git clone https://github.com/emily-ntc/electron-vite-react-serialport.git

# enter the project directory
cd electron-vite-serialport

# install dependency
npm install

# develop
npm run dev

# build (set to windows - will be placed in the /release folder)
npm run build
```


```tree
├── electron                                 
│   ├── main                                 
│   └── preload                               
│
├── release                                  
│   └── {version}
│       ├── {os}-{os_arch}                   
│       └── {app_name}_{version}.{ext}      
│
├── public                                   
└── src                                      
```

