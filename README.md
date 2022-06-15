# system-navigation-bar-rn

This is module for manipulation system navigation bar [ANDROID ONLY]

HOW TO USE ?
- Go To SystemNavigationBar.js
- Copy all module into your utils modules
- Make folder name "SystemNavigationBar" 
- Paste into in it 
- Rename that file to index.js

HOW TO IMPLEMENTATION ?
- import SystemNavigationBar from 'depends-path-u-use'

    <Button
        title="stickyImmersive"
        onPress={async () => {
          const result = await SystemNavigationBar.stickyImmersive();
          console.log('stickyImmersive: ', result);
        }}
      />
  
Happy coding ^^


