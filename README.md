# XML_RPC2

- forked from pear/XML_RPC2
- Ready to use with composer in nette project

##### Example composer.json:
```json
{
  "name": "my/project",
  "description": "This is my project...",
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/ludekslevercz/XML_RPC2"
    },
    {
      "type": "git",
      "url": "https://github.com/ludekslevercz/HTTP_Request2"
    }
  ],
  "require": {
    "php": ">= 5.5.1",
    "nette/nette": "~2.3",
    "pear/xml_rpc2": "dev-nette",
    "pear/http_request2": "dev-nette"
  }
}
```

Author: ludek@slever.cz
