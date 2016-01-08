# cgs_m2_theme
Magento 2 Custom Theme

# Best way to develop
Magento 2 is a beast when set to developer mode. Its slow. For now, its best to run Magento 2 with all caches enabled and have ```grunt``` compile all the ```less``` files.

```
grunt exec
grunt watch
```

This prevents server compile on request which is the reason why its slow. 
