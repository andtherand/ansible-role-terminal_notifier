# Ansible terminal-notifier role

Uses the [terminal-notifier command line tool](https://github.com/julienXX/terminal-notifier) to raise awareness that a playbook has finished.
It's always invoked on the localhost. 

## Requirements

- OSX 10.9 and above
- the terminal notifier mentioned above

# WARNING!
This does not work on Ubuntu Trusty or any other platform except from OSX.
But I had to add a platform to the meta section otherwise it would not be accepted as a valid role.

## Role variables

```yml
---
terminal_notifier_msg: "No errors were encountered! Pat your self on the back and go get some coffee!"
terminal_notifier_sound: default
terminal_notifier_title: "Ansible run finished"
```
## TODO
- Add ability to shout at you when the plays failed!

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style. Would be create if you added unit tests, that's on my todo list aswell :]

1. Fork it
2. Create your feature branch (git checkout -b feature/my-cool-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin feature/my-new-feature)
5. Create new Pull Request

## License

Copyright (c) mychiara | svs under the GPLv2 license.