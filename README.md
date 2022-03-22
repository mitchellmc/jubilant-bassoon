# mermaid testing

## Graph LR
```mermaid
  graph LR;
    DB-->App1;
    App1-->|Older Integrations|App2;
    App1-->|Middle Age Webhooks|Proxy;
    App1-->|Newer Integrations|App3;
    App2-->Proxy;
    App3-->Proxy;
    Proxy-->Outside-World;
```
