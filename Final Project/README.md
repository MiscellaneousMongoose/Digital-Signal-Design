# Space Invaders 3.0
TopModule.vhd
#### Space invaders 2.0 was created a little too difficult to be fun so our mission is to make this game more enjoyable!

### Source Files: 

### 1. [TopModule.vhd](./TopModule.vhd)

### 2. [VGAPixelDriver.vhd](./VGAPixelDriver.vhd)

### 3. [VideoMemory.vhd](./VideoMemory.vhd)

### 4. [debounce.vhd](./debounce.vhd)

### 5. [leddec16.vhd](./leddec16.vhd)

### 6. [ps2_keyboard.vhd](./ps2_keyboard.vhd)


### Constraint Files: 

### 1. [pBoardMasterNexysA7.xdc](./BoardMasterNexysA7.xdc)


### Here is a sample of the game being played in my favorite color setting:

https://user-images.githubusercontent.com/70534986/167667470-bbbe6454-4f57-4a2f-aa4e-d4e80d41dd86.mp4

### Here is what it looks like when the switches controlling color settings are off:

https://user-images.githubusercontent.com/70534986/167957840-aafd130a-7f9a-4f48-8f7b-db3d7a68460e.mov

### Screen samples:

![IMG_2168](https://user-images.githubusercontent.com/70534986/167956710-839623b3-a978-4757-89cd-5429d8cb44ec.jpg)

![0CA285B6-FA69-4AD3-AA5A-F95DC278DD0E](https://user-images.githubusercontent.com/70534986/167956667-797a8010-3e97-4820-9a10-25a6ce4fd686.jpg)

![IMG_2167](https://user-images.githubusercontent.com/70534986/167956692-6a9f9bf8-4bc1-48e8-b178-dd29006a1e26.jpg)

![IMG_2166](https://user-images.githubusercontent.com/70534986/167956677-81350662-5cd3-43d1-80cf-e939b32c77e4.jpg)


### Things to take note of version 2.0:

#### 1. The switches will controll the color schemes.
#### 2. Unable to shoot and move the ship left or right at the same time.
#### 3. The color of the space ship indicates the number of lives remaining.
#### 4. The color of the alien displays the number of lives it has left.
#### 5. The images are hardcoded using 1s and 0s.
#### 6. It seems like there are bits forming the shape of numbers possibly for a score but it was not implemented in the game.
#### 7. If the player presses enter to start a game and does not fire projectiles or move before losing all lives the game will reset as though the player had just pressed enter. 
#### 8. We were only able to get the game working with a wired keyboard plugged into the NEXTYS A7 in which the keys used for input were A, D, SPACE, and ENTER.

### Things changed about the game in 3.0:
#### 1. The width of the space ship was made smaller because in 2.0 it was too wide of a target making the game unreasonably difficult. The width of the ship was changed from 108 to 54 cutting it in half. The ship image was then cut in half and off center which took some time to shift and adjust just right.
#### 2. The speed of the alien fire was increased from 4 to 10 to increase difficulty because if the game is too easy it will not be as enjoyable.
#### 3. The speed of the space ship was increased from 5 to 6 to help with the increased alien fire speed.
#### 4. The speed of the player's fire was increased from a 10 to a 15.
