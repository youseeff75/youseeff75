## Hi, I'm Youssef Ibrahim 👋
![](https://raw.githubusercontent.com/<username>/<username>/main/header.jpeg)

![Flutter CI](https://github.com/<username>/<repo>/workflows/Flutter%20CI/badge.svg)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=<username>.<username>)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/<your-linkedin>/)

```dart
class YoussefIbrahim {
  final String username = "YoussefIbrahim";
  final String name = "يوسف ابراهيم";
  final String position = "Flutter Developer";
  final String portfolio = "https://your-portfolio-link.com";
  final String twitter = "@yourhandle";

  final List<String> skills = [
    "Flutter", "Dart", "Firebase", "REST API", "Bloc", "Provider",
    "GitHub Actions", "Clean Architecture", "UI/UX"
  ];

  @override
  String toString() {
    return "$name | $position";
  }
}

void main() {
  final me = YoussefIbrahim();
  print(me);
}
