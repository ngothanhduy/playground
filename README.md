# jencim
Jenkins Custom Image

# JC Docker Image
Jenkins Controller - Docker Image


# Get list of plugin

Jenkins.instance.pluginManager.plugins.each{
  plugin -> 
    println ("${plugin.getShortName()}:${plugin.getVersion()}")
}