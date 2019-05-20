# ps4-drumrack-M4L
Launch samples from Ableton Drum rack using M4L and PS4 controller. 

# Max 4 live basics
Max for Live is an add-on for Ableton Live that allows you to create instruments, audio effects, and MIDI devices. It can also be used to extend the functionality of hardware controllers and modify clips and parameters within a Live Set.

## Resources to learn Max for Live:

https://www.ableton.com/en/manual/max-for-live/
https://docs.cycling74.com/max5/vignettes/intro/doclive.html
Built-in documentation
## Basic typology

A max patcher is a max document. The building blocks of a patcher are: the object, the message and the comment

Objects perform command actions within a patcher.
Messages allow us to create messages that can be sent to the objects.
Comments allow us to document our patchers to make them easier to understand and revisit our work.

### Object box
An object box is the basic logic element of Max – they contain functions that perform a task, and operate like miniature programs within the larger environment. They can be recognized by their bottom and top outline.

### Message box
Message boxes contain some information (called a message) that can be sent to objects, and can operate as either commands or control data. They can be recognized by their gray background, and do not have an outline.


### Comment box
Comment boxes are used to add text for labeling controls, or for adding comments to your patcher for documentation purposes. They appear to have no background.

Max programs function by passing messages between objects. Object boxes can be connected to one another, and message boxes can be used to originate or process messages that are used to control other objects.
Locking and Unlocking the patcher
Patchers can be in locked or unlocked state.

When a patcher is locked, the intention is that it be used as a program.
When a patcher is unlocked, it will become editable.

You can unlock/lock by selecting/deselecting Edit from the View menu.
The Bang message
The bang message is among the most powerful messages in the Max environment; it causes other objects to trigger their output, and can be used to create matrices of connections that produce complex output.

Most Max objects (including the message box and button ) will interpret a bang as an instruction to perform their main task using whatever information they have available, it's the message that tells many objects to do that thing you do. As a result, sending the bang message to other objects will normally cause them to send messages from their outlets. 

Outlets can be connected to more than one object, and the same message will be sent down each of the patch cords and  multiple patch cords can be connected to a single inlet of an object.

Messages are generated based on the spatial organization of the objects in the patcher, executing from right-to-left.

