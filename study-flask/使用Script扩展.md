####使用Script扩展

```
from flask.ext.script import Manager

app = Flask(__name__)
manager = Manager(app)

if __name__ == '__main__':
    manager.run()
```
