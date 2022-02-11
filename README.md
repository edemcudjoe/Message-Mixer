# Message Mixer

This program encrypts or decrypts messages.

## Contents

* message-mixer.js
* encyptors.js
* super-encoder.js

## Descriptions

* message-mixer.js - Imports encryption modules from encryptors.js and uses it to encrypt text given by user. To call use 'node message-mixer.js encryption-type'. NB. If encryption type is caesar, digit between 0 and 26 must be added after encryption-type.
* encryptors.js - Contains the ciphers used in the encryption process. There are 3 of them - 
  * caesar cipher - encrypts files by shifting characters of the alphabet by a given amount.
  * symbol cipher - encrypts files by replacing select characters with visually similar symbols.
  * reverse cipher - encrypts files by reversing the letters of each word in place.
* super-encoder.js - Imports encryption modules from encrypor.js and encodes words using all 3 ciphers. To encode use 'node super-encoder.js encode'. To decode use 'node super-encoder.js decode'.

## Language/Platform

JavaScript. Execute in Node

