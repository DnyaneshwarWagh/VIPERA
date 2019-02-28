# VIPERA (🐍)

The most simple VIPER module generator for Swift projects.



## Usage

Generate module from default template

```
vipera MyModule
```

You can put your own templates under the `.viper/Templates/` path, e.g. MyTemplate, usage:

```
vipera MyModule MyTemplate
```



## Template variables

You can use the following variables (in file names too):

- module - given module name (capitalized)
- project - based on `.xcodeproj` or `.xcworkspace` name
- author - based on git config
- date - current date in local short format

eg. {module} -> MyModule



## Install

Just clone or download this repository & run:

```
swift run install
```



## License

[WTFPL](https://github.com/BinaryBirds/Shell/blob/master/LICENSE) - Do what the fuck you want to.