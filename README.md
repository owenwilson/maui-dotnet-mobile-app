# maui-dotnet-mobile-app

## install

- install [dotnet on linux](https://github.com/owenwilson/dotnet-sdk-manager)

```sh
sudo dnf install -y dotnet-sdk-8.0
```

- install maui-android

```sh
sudo dotnet workload install maui-android
```

- install [java17](https://github.com/owenwilson/sdk_java_manager)

```sh
sudo dnf install -y java-17-openjdk-devel
```

## uninstall

```sh
sudo dotnet workload uninstall maui-android
```

- clean temporal files

```sh
dotnet workload clean
```

## references

- check out [net maui on linux](https://techcommunity.microsoft.com/blog/educatordeveloperblog/-net-maui-on-linux-with-visual-studio-code/3982195)
- check out [install dotnet sdk manager for linux](https://github.com/owenwilson/dotnet-sdk-manager)
- check out [install android sdk](https://github.com/owenwilson/android-sdk-for-linux)
- check out [install sdk java manager for linxu](https://github.com/owenwilson/sdk_java_manager)
