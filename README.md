# src
useful lib for user

For [Python](Python3),
  1. pip install requests
  2. get the raw module file path as "//raw.githubusercontent.com/{username}/{path-to-module}/*file*.py"
  3. Create a local directory to store the module file r"C:\....", naming as *locationOfModule*
  4. with open(f"{*locationOfModule*}\*file*.py","wb") as f: f.write(request.content)
  5. from *file* import *function*
