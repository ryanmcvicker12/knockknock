
## KnockKnock
KnockKnock is a simple reverse whois lookup CLI which allows you to find domain names owned by an individual person or company, often used for Open Source Intelligence (OSINT) purposes.

### Requirements
`pipenv install`

If you do not have `pipenv` installed, first install it with `pip3 install pipenv`.

### Usage

```console
Usage: k2.py [OPTIONS]

Options:
  -n, --name TEXT        name of the individual person or company to look up.
                         [required]
  -d, --display          display results to console.
  -s, --save             save results to JSON format.
  -t, --type [json|txt]  set file type: 'json' or 'txt'.  [default: json]
  --help                 Show this message and exit.
```

### Example

```console
python3 k2.py -n acme.com -d -s

[:] Sending query...
[:] Parsing response...
acme.com.cn
acme.com.hk
acme.com
acme.hk
acme.ua
aeri-acme.com
alfabetriko.com
alsicohitec.com
armishali.com
armishali.net
armisyatak.com
armisyatak.net
artemiscarpet.com
artepergamino.com
avs-acme.com
beyazzz.com
beyazzzyatak.com
bh-acme.com
blue-acme.com
bodega-acme.com
c-acme.com
clinemotorsports.com
decamerondeboccaccio.com
dogutasit.com
dosheg.net
doshegyatak.net
dp15.us
edicionesfacsimiles.com
geceyatak.com
gruntwork-acme.com
grviatges.cat
halipasaji.com
hertzber.gs
hf-acme.com
hkboy.org
hkgirl.org
hkgonline.com
hkhelp.net
hkhelp.org
hkrepair.net
holidayindustry.net
investigate-acme.com
ipex-live.com
ipex.band
ipex.cc
ipex.club
ipex.design
ipex.net.cn
ipex.pub
ipex.rocks
ipex.studio
ipex.tech
ipex.video
ipex.vip
kupahotel.com
kwuntong.org
mllongo.com
poskanzer.org
pratoexclusive.com
pratohali.com
propertyfromturkey.com
r-box.com.cn
raiba.cn
revue-acme.com
reynaudio.cn
reynaudio.com.cn
royal-acme.com
scriptorium.net
suministrosacme.com
sweatersandbeyond.com
test-acme.com
thehfg.co.uk
xiaoweilu.cn
[:] Saving results to JSON file...
[:] Saved to domains.json
[:] Found 73 printable domains!
```

### Disclaimer
This tool is courtesy of the free tier of ViewDNS (non-API) which is also limited to showing 500 domains for a given query &mdash; please use responsibly.

---

&copy; 2018 Leonid Hartmann