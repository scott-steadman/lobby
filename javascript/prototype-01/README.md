# Lobby Prototype 1

Problem: I don't want to have to run a server in order to support my lobby.

Experiment: Can I set up a WebRTC connection by using copy/paste via chat app (eg Discord)
to create a WebRTC connection.

## To run

```sh
rbenv shell {version}
gem install webrick
ruby -run -ehttpd . -b 0.0.0.0 -p 3000
```

## Notes

[STUN server list](https://gist.github.com/mondain/b0ec1cf5f60ae726202e)
