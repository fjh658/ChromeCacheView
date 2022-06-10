# ChromeCacheView for macOS

- Windows version of nirsoft's ChromeCacheView wrapped by Wineskin on macOS.

- Used to diagnose chrome, cef ([Chromium Embedded Framework](https://github.com/chromiumembedded)) cache related issues

- Usage
  - chrome cache view dmg
   ![image](https://user-images.githubusercontent.com/5550316/171787682-53606e44-2cf8-4c42-adb8-5f650c163db1.png)
  - wineskins remove quarantine
  ```
   xattr -rd com.apple.quarantine /Applications/ChromeCacheView.app
  ```

 
  - Open cache dialog

   ![image](https://user-images.githubusercontent.com/5550316/170872979-3aaa8ffd-dc77-478d-b37a-0a0c1e5ee573.png)

  - ~/Library/Caches/Google/Chrome/Default/Cache

    Note: **z:** driver

    ```
    eg: /Users/john/Library/Caches/Google/Chrome/Default/Cache
    ```

    ![image](https://user-images.githubusercontent.com/5550316/170872992-f1a8510a-e957-42a0-81c8-7155613b29cf.png)


    ![image](https://user-images.githubusercontent.com/5550316/170873005-19186374-823d-4f47-bf8e-61a4b024d715.png)


