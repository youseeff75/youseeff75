# Hi, I'm Youssef Ibrahim 👋
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=YoussefIbrahim.YoussefIbrahim)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/your-linkedin/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?logo=github&logoColor=white)](https://github.com/YoussefIbrahim)
[![Twitter](https://img.shields.io/badge/Twitter-blue?logo=twitter&logoColor=white)](https://twitter.com/yourhandle)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:yourmail@gmail.com)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?logo=whatsapp&logoColor=white)](https://wa.me/201234567890)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?logo=facebook&logoColor=white)](https://facebook.com/yourprofile)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white)](https://instagram.com/yourprofile)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white)](https://your-portfolio-link.com)

---

## 🌟 About Me
- 👨‍💻 Flutter Developer متخصص في تطوير تطبيقات Android & iOS  
- 📱 خبرة في **Bloc, Provider, Riverpod**  
- 🔥 مهتم بالـ **Clean Architecture & UI/UX**  
- ☁️ أتعامل مع **Firebase, REST APIs, GitHub Actions**  

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

  final Map<String, String> contacts = {
    "LinkedIn": "https://www.linkedin.com/in/your-linkedin/",
    "GitHub": "https://github.com/YoussefIbrahim",
    "Twitter": "https://twitter.com/yourhandle",
    "Gmail": "mailto:yourmail@gmail.com",
    "WhatsApp": "https://wa.me/201234567890",
    "Facebook": "https://facebook.com/yourprofile",
    "Instagram": "https://instagram.com/yourprofile",
    "Portfolio": "https://your-portfolio-link.com"
  };

  @override
  String toString() {
    return "$name | $role | Skills: ${skills.join(", ")}";
  }
}

void main() {
  final me = YoussefIbrahim();
  print(me);
}
