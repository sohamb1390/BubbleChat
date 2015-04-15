BubbleChat
==========
BubbleChat is an iOS peer-to-peer chat program that uses Bluetooth LE as its communications channel.
Why BubbleChat
--------------
I developed BubbleChat as an experiment to see whether it would be possible to build a somewhat useful chat application that used Bluetooth LE as its communications channel.

BubbleChat defines its own Bluetooth LE service (and set of characteristics for that service) that allows nearby peers to discover one another and exchange location updates and status messages.

The concept behind BubbleChat is simple: Peers that you can communicate with over Bluetooth LE are in your "bubble". Peers come and go from your bubble as they move near to you and away from you. You can see which peers are in your bubble and where they are relative to you in the Nearby Peers view. You can chat with peers that are in your bubble in the Bubble view.

BubbleChat acts as both a Bluetooth LE accessory itself and as a consumer of its own Bluetooth LE accessory, so it's pretty useful as an Bluetooth LE programming sample for iOS.
License
-------
BubbleChat is released under an MIT license, meaning you're free to use it in both closed and open source projects. However, even in a closed source project, please include a publicly-accessible copy of BubbleChat's copyright notice, which you can find in the LICENSE file.

Feedback
--------
If you have any questions, suggestions, or contributions to BubbleChat, please [contact me](mailto:brianlambert@softwarenerd.org).
