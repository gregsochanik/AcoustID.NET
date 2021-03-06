AcoustID.NET
============

AcoustID fingerprinter and webservice access in C#. See http://acoustid.org/ for information about the AcoustID project.

The original code for this project can be found at https://bitbucket.org/acoustid.

##Features.
* AcoustID fingerprint calculation.
* AcoustID webservice access (request only, submit not implemented)
* *Fingerprinter* example application

The example application shows how to decode audio files using [NAudio](http://naudio.codeplex.com/) or [Bass](http://www.un4seen.com/bass.html).

##Configuration.
If you want to use the AcoustID webservices in your application, you need to get an API key from http://acoustid.org/. Once you have the key, register it with AcoustID.NET by setting
```
AcoustID.Configuration.ApiKey = "APIKEY";
```

##License.

LGPL v2.1 (see COPYING.txt at https://bitbucket.org/acoustid/chromaprint/src)
