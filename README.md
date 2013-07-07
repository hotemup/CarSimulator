This is the simulation platform for the self driving vehicle at https://github.com/derivatived/self-driving-car.
It is being built in the Unity3D Game Engine.  Since Unity projects have large amounts of metadata that end up clogging a git repo and breaking the project, we are storing them as zipped archives so they are tracked as binary files.  To use, simply unpack the archive and open it up in Unity3D.  It will run with the demo AI.  For information on how to hook in your own AI, or help contribute the project, please see the wiki.

The car simulation AI can be controlled over a network connection using sockets, as seen in SampleAIServer.
