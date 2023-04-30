# R.V.S-meditation-
This will take your stress out with the simple meditation 
>>> import urllib3
>>> http = urllib3.PoolManager()
>>> resp = http.request("GET", "http://httpbin.org/robots.txt")
>>> resp.status
200
>>> resp.data
b"User-agent: *\nDisallow: /deny\n"
Installing
urllib3 can be installed with pip:

$ python -m pip install urllib3
Alternatively, you can grab the latest source code from GitHub:

$ git clone https://github.com/urllib3/urllib3.git
$ cd urllib3
$ pip install .
