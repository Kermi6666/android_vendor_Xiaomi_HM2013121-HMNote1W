# android_vendor_Xiaomi_HM2013121-HMNote1W

  This is a vendor tree for Xiaomi RedmiNote1W(HM2013121) which is based on MT6592 SoC. 
  Working on cm12.1 source
  Powered by Kermi.
  Thanks for ferhung!!!


* full build
        
        # source build/envsetup.sh
        # lunch cm_HM2013121_userdebug
        # brunch HM2013121


# In China, we must skip to get 204 from Google server.
  * Change of Android 5.1 source to skip network validation in some environment like China can't connect to http://clients3.google.com/generate_204. 

  To see: 
    [Skip_network_validation](http://github.com/Kermi6666/Skip_network_validation)
