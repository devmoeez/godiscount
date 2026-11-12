# GoDiscount

A university project: a deals and discount marketplace app built with Flutter, developed at the University of Management and Technology (UMT), Lahore. Customers discover offers, merchants publish and manage deals, and admins moderate the platform. An AI recommendation module surfaces deals relevant to each user.

## **1. Features**

- **Auth:** email and social sign-in through Firebase Authentication, role-based routing (customer, merchant, admin)
- **Merchant:** create, edit and schedule deals, track redemptions
- **Admin:** approve merchants, moderate deals, platform analytics
- **AI Recommendations:** personalized deal feed based on user activity

## **2. Tech Stack**

| Layer | Technology |
|---|---|
| UI | Flutter |
| State management | Riverpod |
| Models | Freezed, json_serializable |
| Navigation | GoRouter |
| Backend | Firebase (Auth, Firestore, Storage, Cloud Functions) |
| Architecture | MVVM |

## **3. Project Structure**

```
lib/
  core/            # theme, constants, utilities, router
  data/            # models, repositories, Firebase services
  features/
    auth/          # views, view models
    merchant/
    admin/
    recommendations/
  main.dart
```

## **4. Getting Started**

```bash
git clone https://github.com/devmoeez/godiscount.git
cd godiscount
flutter pub get
flutterfire configure          # link your Firebase project
dart run build_runner build --delete-conflicting-outputs
flutter run
```

## **5. Modules Completed**

- [x] Auth module
- [x] Merchant module
- [x] Admin module
- [x] AI recommendation module

## **6. Author**

**Moeez Hashmi**, BS Cybersecurity, UMT Lahore

*Built for academic purposes. Not a production or publicly released app.*
