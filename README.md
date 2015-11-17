# pwdhash-firefox
PwdHash extension for firefox

## description
Automatically generates per-site passwords if you prefix your password with @@ or press F2 beforehand.
Prevents JavaScript from reading your password as it is typed.
The same password will be generated at each subdomain: a.example.com matches b.example.com, a.example.co.uk
matches b.example.co.uk, but a.co.uk and b.co.uk are different.

Hashed passwords can also be generated at https://www.pwdhash.com/

## roadmap

* make it restartless (restructure code)
* update to build with jpm (currently built by just zipping into an XPI file)

## feature brainstorm

* activate for all password fields (press F2 to deactivate for current page, needs new option window)

