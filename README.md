# ePickleDB
There are several key-value store packages. PickleDB is among the one of them written in Python, JSON based. ePickleDB is an enhanced version of PickleDB for web applications.

###### Improvement(s)

- Fixed the error while loading just after manipulating database with some web frameworks such as Flask

#### Installation

```
pip install epickled
```

To replace your PickleDB with ePickleDB in your app, import `epickledb` as `pickledb`.

```
import epickledb as pickledb
```
