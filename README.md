# Install Protocol Buffers, Objective C

   1.`ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"`
   
   2.`brew install automake`
   
   3.`brew install libtool`
   
   4.`brew instal protobuf`

   5.`clone protobuf-objc`
   
   6.`./autogen.sh`

  7.`./configure`
  
   8.`sudo make && make install`

#Compile ".proto" files. 

 
###Compile ARC support.
   `protoc --plugin=/usr/local/bin/protoc-gen-objc-arc person.proto --objc_out="./"`

###Compile without ARC.
   `protoc --plugin=/usr/local/bin/protoc-gen-objc person.proto --objc_out="./"`




# Protocol Buffers, Objective C

An implementation of Protocol Buffers in Objective C.

Protocol Buffers are a way of encoding structured data in an efficient yet extensible format.
This project is based on an implementation of Protocol Buffers from Google.  See the
[Google protobuf project][g-protobuf] for more information.

[g-protobuf]: http://code.google.com/p/protobuf/


# Credits

Booyah Inc.
-------------------------------------------------------------------------------
- Jon Parise <jon@booyah.com>


Google Protocol Buffers, Objective C
-------------------------------------------------------------------------------
- Cyrus Najmabadi  (http://code.google.com/p/metasyntactic/wiki/ProtocolBuffers)
- Sergey Martynov  (http://github.com/martynovs/protobuf-objc)


Google Protocol Buffers
-------------------------------------------------------------------------------
- Kenton Varda, Sanjay Ghemawat, Jeff Dean, and others