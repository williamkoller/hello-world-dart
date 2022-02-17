## Hello World Dart

### How install Dart SDK

- Install using `apt-get`:

```
sudo apt-get update
sudo apt-get install apt-transport-https
sudo sh -c 'wget -qO- https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
sudo sh -c 'wget -qO- https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > /etc/apt/sources.list.d/dart_stable.list'
```
- Then installl the Dart SDK:

```
sudo apt-get update
sudo apt-get install dart
```
- Verify version installed

`dart --version`

```
Dart SDK version: 2.16.1 (stable) (Unknown timestamp) on "linux_x64"
```

- Hello World in Dart

```
void main() {
  print("Hello, world");
}
```

- running file in dart

`dart run hello_world.dart`

```
Hello, world
```