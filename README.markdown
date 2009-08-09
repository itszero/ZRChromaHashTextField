ZRChromaHashTextField
=====================

## A sexy, secure visualization of password field input

The Chroma-Hash is originally a jQuery plugin which provided a dynamic visualization of text-field value using ambient color bars.

Now, it has been ported to Cappuccino framework. All you have to do is use ZRChromaHashTextField, and voila, now your password input field has such feature. :D

## Demo

[Seeing](http://itszero.github.com/ZRChromaHashTextField/) is believing. 

## Usage

<code>
@import "ZRChromaHashTextField.j"
var chromaField = [ZRChromaHashTextField textFieldWithStringValue:""
    placeholder:"ChromaHash-Powered Password TextField" width:600];
[chromaField sizeToFit];
[what_ever_the_view addSubview: chromaField];
</code>

It provides the static initializer **textFieldWithStringValue:placeholder:width:** just like the ordinary CPTextField. However, this is the only available static initializer for now.

## License

ZRChromaHashTextField is licensed under the MIT License:

  Copyright (c) 2009 Chien-An "Zero" Cho (http://itszero.org/)

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.

## Credit

ZRChromaHashTextField is porting the "Chroma-Hash" from jQuery to Cappuccino web framework. The Chroma-Hash is created by Mattt Thompson. See [its github project](http://github.com/mattt/Chroma-Hash).

The "Chroma-Hash" project is inspired in part by Arc90 Labs' HashMask  
[http://lab.arc90.com/2009/07/hashmask.php](http://lab.arc90.com/2009/07/hashmask.php)

I also used the MD5 hashing implementation from Paul Johnston, it is distributed under the BSD License. You may find more information [here](http://pajhome.org.uk/crypt/md5)

