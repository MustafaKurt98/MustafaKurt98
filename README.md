```dart
class MustafaKurt {
  final String name;
  final String username;
  final String location;
  final int age;

  MustafaKurt({
    required this.name,
    required this.username,
    required this.location,
    required this.age,
  });

  // Named constructor for default values
  MustafaKurt.defaultProfile()
      : name = "Mustafa",
        username = "Kurt",
        location = "Ankara, Turkey",
        age = 26;

  @override
  String toString() {
    return 'Name: $name, Username: $username, Location: $location, Age: $age';
  }
}

void main() {
  var me = MustafaKurt.defaultProfile();
  print(me);
}
```


- 📱 I’m interested in mobile development & UI-UX
- 💙 I’m currently learning Dart-Flutter and Figma
- 🧑🏻‍💻 I'm trying to learn Node.js recently

<!---
MustafaKurt98/MustafaKurt98 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
