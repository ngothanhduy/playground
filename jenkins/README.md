# Jenkins Bootstrap

### Get list of plugin from the existence Jenkins
```
Jenkins.instance.pluginManager.plugins.each{
  plugin -> 
    println ("${plugin.getShortName()}:${plugin.getVersion()}")
}
```

### Build
```
make build
```

### Run
```
make run
```