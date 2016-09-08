# PookieEventBus

This is a single file Class library for android. It has no dependencies. Just copy paste the file and use it.
for using this Event Bus you need to follow simple two steps:

## first:
  
### subscribe Event Bus
```PookieEventBus.getInstance().subscribe(receiver, key);```



 
```PookieEventBus.getInstance().subscribe(this, key);```

### then onEvent Method will be implimented so use it like
```@Override
    public void onEvent(String term, Object object) {
       //todo check terms 
       
    }
```

### publish Event to Event Bus

``` PookieEventBus.getInstance().publish(key,object);```

