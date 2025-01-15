# Quick Start

Place `home.html` and `favicon.png` in the `/www` directory.

Then, access your OpenWrt IP at `/home.html` to get started!

# Config

Add your services to the service list in `home.html`:

``` javascript
// Define the service list
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
    // Add or remove service items here
];
```

# Preview
<div style="display: flex; justify-content: space-around; align-items: center;">
  <img src="https://github.com/user-attachments/assets/1b2298f0-f80a-41f9-af6c-7f7d0647480b" alt="Image 1" style="width: 45%; height: auto;">
  <img src="https://github.com/user-attachments/assets/b5ae113f-d4e1-4524-847b-744ab548e9ab" alt="IMG_1029" style="width: 45%; height: auto;">
</div>




![image](https://github.com/user-attachments/assets/1b2298f0-f80a-41f9-af6c-7f7d0647480b)

<img src="https://github.com/user-attachments/assets/b5ae113f-d4e1-4524-847b-744ab548e9ab" alt="IMG_1029" width="300" height="649">
