# File Specifications

---

* Color Space:
	* Adobe RGB (1998), sRGB, or Grayscale 2.2  gamma
	* Not ProPhoto RGB, Dot Gain 20% or any 1.8 gamma color space
* 8bit preferred. 16bit is allowed and will be converted to 8bit by Thrive RIP-Queue
* File types: JPG or TIF not **PSD** 
* Compression: None is preferred LZW for 8bit is ok and ZIP is not supported
* Files should be sized with borders to 100% of print size at 300ppi

!!! Warning
    Files with 1.8 gamma will be assigned 2.2 gamma in Thrive causing them to print dark. Any file with 1.8 gamma must be converted to 2.2 gamma beforehand.