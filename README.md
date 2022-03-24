# CustomCharacterController
A Unity package containing a demo scene for a custom character controller asset I made.

  This unity package was exported from a project using Unity version 2020.3.32f1
I want to work on thoroughly commenting the CharacterBody and CharacterController scripts, but for now they're only lightly commented.

  This character controller does not use the rigidbody physics system, this means that any movement feature that hasn't already been written in needs to be. However I'm hoping that this asset offers a good starting point for those who are interested in making their own character controller from scratch with the help of Unity's existing physics API.

  I beleive this approach offers more ways to fine tune character movement compared to using Unity's rigidbody system. Almost everything is done through custom MonoBehavior scripts (aside from basic mesh casting and overlap based collision detection). Because everything going on with the character's movement is accessable within two scripts, the possibilities for adding additional functionality and making adjsutments are endless. ✨🌠✨
