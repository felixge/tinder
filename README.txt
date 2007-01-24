= Tinder

Tinder is a library for interfacing with Campfire, the chat application from 37Signals.

  campfire = Campfire.new 'mysubdomain'
  campfire.login 'myemail@example.com', 'mypassword'
  room = campfire.create_room 'New Room', 'My new campfire room to test tinder'
  room.rename 'New Room Name'
  room.speak 'Hello world!'
  room.speak "my pasted\ncode", :paste => true
  room.destroy

== Requirements

* Active Support
  gem install activesupport
* Hpricot
  gem install hpricot

== ToDo

* Tests! (unit and remote)
* Log in via guest url
* SSL