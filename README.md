# Hi, I'm Youssef Ibrahim 👋
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=<username>.<username>)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/<your-linkedin>/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white)](https://github.com/<username>)
[![Twitter](https://img.shields.io/badge/Twitter-blue?logo=twitter&logoColor=white)](https://twitter.com/<yourhandle>)

---

## 🌟 About Me
- 👨‍💻 Flutter Developer متخصص في تطوير تطبيقات Android & iOS.  
- 📱 خبرة في **State Management (Bloc, Provider, Riverpod)**.  
- 🔥 مهتم بالـ **Clean Architecture & UI/UX**.  
- ☁️ أتعامل مع **Firebase, REST APIs, GitHub Actions**.  

---

## 🚀 Tech Stack
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)

---

## 💻 Code about me

```dart
class YoussefIbrahim {
  final String username = "YoussefIbrahim";
  final String name = "يوسف ابراهيم";
  final String role = "Flutter Developer";
  final List<String> skills = [
    "Flutter", "Dart", "Firebase",
    "REST API", "Bloc", "Provider",
    "Riverpod", "Clean Architecture", "UI/UX"
  ];

  @override
  String toString() {
    return "$name | $role | Skills: ${skills.join(", ")}";
  }
}

void main() {
  final me = YoussefIbrahim();
  print(me);
}
