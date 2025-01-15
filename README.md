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
<p align="center">
  <img src="https://github.com/user-attachments/assets/1b2298f0-f80a-41f9-af6c-7f7d0647480b" alt="Image 1" width="400">
  <img src="https://github.com/user-attachments/assets/b5ae113f-d4e1-4524-847b-744ab548e9ab" alt="IMG_1029" width="200">
</p>
