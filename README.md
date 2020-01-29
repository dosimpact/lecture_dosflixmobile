# dosflix App

# 설치 이슈

- (npm i expo-cli -g ) //SDK 36 버전으로 업그래이드 되면서, expo client도 업글해야 작동하는 이슈발생
- sdk 36버전에 따른 업데이트 절차 - 문서를 보는게 최고, how to upgrade 라고 나옴. expo upgrade 하나면 됨.
- expo client (모바일 앱) 이것도 지우고 다시 깔아 , 클라이언트도 업데이트가 되야함.

# 1.0 Expo Init (5:07)

expo init [AppName]
yarn add prop-types styled-components axios @expo/vector-icons expo-font
yarn add react-navigation react-navigation-tabs react-native-reanimated react-native-gesture-handler react-native-screens

# 1.1 Introduction to Expo (6:24)

- Expo : iOS,Android 빌드를 대신 해준다. | air update라고 앱스토어의 업그래이드 없이 js만 앱에서 다시 다운받아서 앱업데이트 가능 |
- iOS는 QR스캔이 안되므로, expo 사이트 로그인 + 모바일 로그인 하면 project들이 뜬다. 그걸 눌러 할것.

# 1.2 Pre Loading Assets (10:09)

- App.js 에서 폰트를 미리 프리로드 하는 법을 배움.

# 1.3 Constants and Screens Set Up (5:45)

---

# 2.0 Creating a Tab Navigation (9:23)

[https://reactnavigation.org/docs/en/getting-started.html](https://reactnavigation.org/docs/en/getting-started.html)
[https://reactnavigation.org/docs/en/bottom-tab-navigator.html](https://reactnavigation.org/docs/en/bottom-tab-navigator.html)

# 2.1 Custom Icons for the Tab Navigation (11:00)

# 2.2 Live Reloading vs Hot Reloading (2:43)

# 2.3 Introduction to Stack Navigation (6:35)

# 2.4 Creating a Stack Navigation (13:04)

# 2.5 Styling Stack Navigators (13:09)

# 2.6 Finishing Up (5:49)