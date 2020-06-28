## Examples of handlers

```
  handlers:
  - name: restart_service
    service: 
      service: httpd
      state: started
      enabled: true
```

jinja template included
