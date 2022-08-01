This is the source documentation of FreeCAD. Read it online at https://freecad.github.io/SourceDoc/

#### To regenerate it and submit a PR here

1. Fork this repo

2. On your machine:
```
git clone https://github.com/FreeCAD/FreeCAD
cd FreeCAD
mkdir build
cd build
mkdir -p doc/SourceDocu/html
cd doc/SourceDocu/html
git clone your-fork-url
cd ../../..
cmake -DBUILD_QT5=ON -DPYTHON_EXECUTABLE=/usr/bin/python3 ..
make WebDoc
cd doc/SourceDocu/html
git commit
git push
```

3. Then go to your fork and make a Pull Request

Documentation at https://wiki.freecadweb.org/index.php?title=Source_documentation
