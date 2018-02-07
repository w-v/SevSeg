SevSeg
======
 Copyright 2016 Dean Reading

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at 
 http://www.apache.org/licenses/LICENSE-2.0
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.
* * *

Checkout [the original project](https://github.com/DeanIsMe/SevSeg)

 This branch implements :  
- blinking digits (or character)
- scrolling text
- a shift register using 2 pins (the display is driven with 6 pins total)

 As of now, I use it in a particular project, and it is specifically tuned for it. Some features of the original project are not present, and it there is no options to support other setups. That includes : 
- discarding the code for displays with resistors on segments  
- not checking when to update as I do it with an interrupt routine in my application
- There is no intend to support other shift registers than the SN74595

I might add support for more general setups in the future
