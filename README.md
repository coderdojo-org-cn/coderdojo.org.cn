# coderdojo.org.cn
CoderDojo中国

## Dependencies
Install with `sudo` or root user please.
```
pip install pelican markdown
```

## Prepare source
```bash
git clone https://github.com/coderdojo-org-cn/coderdojo.org.cn.git
cd coderdojo.org.cn
git submodule update --init
```

## Generate pages
```bash
make publish
```

## Preview through localhost
```bash
make serve
```

then you can access it through http://localhost:8000

## Publish through GitHub
```bash
make github
```

## Links
* [Pelican docs](https://docs.getpelican.com/en/stable/)
