# ReactNative-Theoretical
Basic knowledge Of react native and theoretical Concept



What Is React Native?

React Native is a JavaScript framework for writing real, natively rendering mobile applications for iOS and Android. It’s based on React, Facebook’s JavaScript library for building user interfaces, but instead of targeting the browser, it targets mobile platforms. In other words: web developers can now write mobile applications that look and feel truly “native,” all from the comfort of a JavaScript library that we already know and love. Plus, because most of the code you write can be shared between platforms, React Native makes it easy to simultaneously develop for both Android and iOS.



Advantages of React Native

The fact that React Native actually renders using its host platform’s standard rendering APIs enables it to stand out from most existing methods of cross-platform application development, like Cordova or Ionic. Existing methods of writing mobile applications using combinations of JavaScript, HTML, and CSS typically render using web views. While this approach can work, it also comes with drawbacks, especially around performance. Additionally, they do not usually have access to the host platform’s set of native UI elements. When these frameworks do try to mimic native UI elements, the results usually “feel” just a little off; reverse-engineering all the fine details of things like animations takes an enormous amount of effort, and they can quickly become out of date.


React Native Features

Following are the features of React Native −

React − This is a Framework for building web and mobile apps using JavaScript.

Native − You can use native components controlled by JavaScript.

Platforms − React Native supports IOS and Android platform.

Example

import React, { Component } from 'react'
import { View, Text } from 'react-native'

const App = () => {
   return (
      <View>
         <View>
            <Text>This is my text</Text>
         </View>
      </View>
   )
}
export default App





