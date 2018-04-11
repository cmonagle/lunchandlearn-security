# Paint Encryption Activity
This activity is almost directly copied from [this fantastic video](https://www.youtube.com/watch?v=3QnD2c4Xovk&t=2s).

## Requirements
1. Two volunteers
1. Several colours of paint
1. Two small trays and something to mix it with.
1. Two folders (or some sort of privacy screen)

## Activity
1. Kim is trying to send Lauren a secret message, but everyone else in the room can see (and in theory, reproduce) all communication.
1. Kim and Lauren each select a colour (paint tube), which they keep private. These are their respective _private keys_.
1. A third colour is selected (this is the _public key_).
1. In private, Kim and Lauren each combine equally sized amounts of their private colours and the public colour. Because it's easy to mix two colours and get a third, but virtually impossible to determine the exact two colours from that third colour, this is a _one way function_.
1. They each send eachother their mixed colours.
1. Finally, they both combine the mixed colour with their private colour.
1. The resulting colour, on both sides, is a mixture of both private colours and the public colour. This colour couldn't be created by the rest of the room and is now their common key.
