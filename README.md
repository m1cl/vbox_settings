Virtualbox OSX Settings

  ´´´shell VBoxManage modifyvm "osx" --cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff                                                              ´´´
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac11,3"                                                  ´´´ 
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0"                                                       ´´´
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0"                                                       ´´´
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Iloveapple"                                                 ´´´
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/smc/0/Config/DeviceKey"                                                                    ´´´
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal(c)AppleComputerInc" ´´´                                      
  ´´´shell VBoxManage setextradata "osx" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1                                                          ´´´
