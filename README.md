### google-api-python-client
---
https://github.com/googleapis/google-api-python-client


```py
// tests/test_channel.py
from __future__ import absolute_import

__author__ = 'xxx@google.com ( Joe Gregorio)'

import unittest2 as unittest
import datetime

from googleclient import channel
from googleapiclient import errors

class TestChannel(unittest.TestCase):
  def test_basic(self):
    ch = channel.Channel('web_hook', 'myid', 'mytoken',
      'http://example.org/callback',
      expiration=0,
      params={'extra': 'info'},
      resource_id='the_resource_id',
      resource_uri='http://example.com/resource_1')


```

```
```

```
```

