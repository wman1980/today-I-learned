# How to simulate Android Kill Process for Your Debug Apps within AndroidStudio?

To simulate app kill process you have to do the following things:
1. Debug your app as normal by hitting _debug app_ button or using keyshortcut `^D`
2. Move your app to background by pressing androids _Overview_ or _Home_ button
3. Press _Kill process_ button in AndroidStudio within _Device Explorer_->_Processes_
4. Reattach debugger to android process via _Run_->_Attach debugger to android process_
5. Open your app from _Overview_ list  

![Screenshot of DeviceExplorer in AndroidStudio with new UI](/android/assets/terminate_app_process_by_os_1.png)

