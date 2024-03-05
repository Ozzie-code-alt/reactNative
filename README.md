# React Native 101

- `<Text>` is similar to `p` tag which handles texts
- `<View>` is similar to `div` it acts as a container and by defaults it uses flexbox layout
- `<TouchableOpacity>` more of like an animation / interactive element that fades in opacity when pressed
- `<ActivityIndicater>` shows a spinner or loading indicator

# Important

- `<Flatlist>` used for rendering long list of items. Similar to `map()`
- `<ScrollView>` container that holders components to provice scrollbar
- `<SafeAreView>` ensures that content is within visible area, not inside notches etc.


instaling expo 
`npx create-expo-app@latest -e with-router ./`  i have no idea what -`e` is `./` is to create on current directory

start dev
`npx expo start --tunnel` --tunnel flag for ditching firewalls
for tunneling :

`npm install --global @expo/ngrok@^4.1.0`

# if bundler failed while tunneling refer to this stack overflow thread
https://stackoverflow.com/questions/77869840/how-to-fix-react-native-error-after-updating-expo-to-50-0