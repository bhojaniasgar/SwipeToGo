# React Native Swipe to go

This dependency is used when you have to perform some action while you have to swipe and do any call 

# Installation 
 `yarn add react-native-swipetogo`

 `npm install react-native-swipetogo`
 
# usage
```
import SwipeTogo from react-native-swipetogo
```
```
 <SwipeTogo
    opacity={1}
    width={45}
    buttonSize={45}
    buttonColor={'Red'}
    borderRadius={30}
    backgroundColor={'Green'}
    okButton={{ visible: true, duration: 400 }}
    onVerified={() => alert('Task COmepletd)}
    icon={
          <View>
          <Image
         source={} // place your image path 
autoPlay
 resizeMode='contain'
/>
</View>
}
>
<Text>Swipe Here</Text>
</SwipeTogo>
```