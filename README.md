# Quick Start
将 `home.html` 、 `favicon.png` 放置在 `/www` 目录下。

访问你的 OpenWrt IP/home.html 即可！

# Config
在 `home.html` 中服务列表添加你的服务即可：
```
        // 定义服务列表
        const services = [
            { 
                name: 'OpenWrt', 
                port: 80,
                path: ''
            },
            { 
                name: 'Qinglong', 
                port: 5700,
                path: ''
            },
            { 
                name: 'Clash', 
                port: 9090,
                path: '/ui/yacd/#/'
            },
            {
                name: 'Alist',
                port: 5244,
                path: ''
            }
            // 在这里添加或删除服务项
        ];
```

# Preview
![image](https://github.com/user-attachments/assets/1b2298f0-f80a-41f9-af6c-7f7d0647480b)

<img src="https://github.com/user-attachments/assets/b5ae113f-d4e1-4524-847b-744ab548e9ab" alt="IMG_1029" width="300" height="649">
