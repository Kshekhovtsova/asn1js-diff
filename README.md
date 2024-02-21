asn1js-diff
======
This is a fork of the popular https://lapo.it/asn1js/ tool which allows to view a diff of two ASN.1 structures side-by-side (work in progress).

asn1js is a JavaScript generic ASN.1 parser/decoder that can decode any valid ASN.1 DER or BER structures.

Usage 
-----------
[asn1js-diff on GitHub Pages](https://kshekhovtsova.github.io/asn1js-diff/)

You can load two ASN.1 structures by passing base64 values to `left` and `right` query parameters: [https://kshekhovtsova.github.io/asn1js-diff/?left=<example_cert1>&right=<example_cert2>](https://kshekhovtsova.github.io/asn1js-diff/?left=MIIBfzCCATGgAwIBAgIUfI5kSdcO2S0-LkpdL3b2VUJG10YwBQYDK2VwMDUxCzAJBgNVBAYTAklUMQ8wDQYDVQQHDAZNaWxhbm8xFTATBgNVBAMMDFRlc3QgZWQyNTUxOTAeFw0yMDA5MDIxMzI1MjZaFw0zMDA5MDIxMzI1MjZaMDUxCzAJBgNVBAYTAklUMQ8wDQYDVQQHDAZNaWxhbm8xFTATBgNVBAMMDFRlc3QgZWQyNTUxOTAqMAUGAytlcAMhADupL_3LF2beQKKS95PeMPgKI6gxIV3QB9hjJC7_aCGFo1MwUTAdBgNVHQ4EFgQUa6W9z536I1l4EmQXrh5y2JqASugwHwYDVR0jBBgwFoAUa6W9z536I1l4EmQXrh5y2JqASugwDwYDVR0TAQH_BAUwAwEB_zAFBgMrZXADQQBvc3e-KJZaMzbX5TT9kPP9QH8fAvkAV_IWDxZrBL9lhLaY0tDSv0zWbw624uidBKPgmVD5wm3ec60dNVeFZYYG&right=MIIEkjCCA3qgAwIBAgIQCgFBQgAAAVOFc2oLheynCDANBgkqhkiG9w0BAQsFADA_MSQwIgYDVQQKExtEaWdpdGFsIFNpZ25hdHVyZSBUcnVzdCBDby4xFzAVBgNVBAMTDkRTVCBSb290IENBIFgzMB4XDTE2MDMxNzE2NDA0NloXDTIxMDMxNzE2NDA0NlowSjELMAkGA1UEBhMCVVMxFjAUBgNVBAoTDUxldCdzIEVuY3J5cHQxIzAhBgNVBAMTGkxldCdzIEVuY3J5cHQgQXV0aG9yaXR5IFgzMIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAnNMM8FrlLke3cl03g7NoYzDq1zUmGSXhvb418XCSL7e4S0EFq6meNQhY7LEqxGiHC6PjdeTm86dicbp5gWAf15Gan_PQeGdxyGkOlZHP_uaZ6WA8SMx-yk13EiSdRxta67nsHjcAHJyse6cF6s5K671B5TaYucv9bTyWaN8jKkKQDIZ0Z8h_pZq4UmEUEz9l6YKHy9v6Dlb2honzhT-Xhq-w3Brvaw2VFn3EK6BlspkENnWAa6xK8xuQSXgvopZPKiAlKQTGdMDQMc2PMTiVFrqoM7hD8bEfwzB_onkxEz0tNvjj_PIzark5McWvxI0NHWQWM6r6hCm21AvA2H3DkwIDAQABo4IBfTCCAXkwEgYDVR0TAQH_BAgwBgEB_wIBADAOBgNVHQ8BAf8EBAMCAYYwfwYIKwYBBQUHAQEEczBxMDIGCCsGAQUFBzABhiZodHRwOi8vaXNyZy50cnVzdGlkLm9jc3AuaWRlbnRydXN0LmNvbTA7BggrBgEFBQcwAoYvaHR0cDovL2FwcHMuaWRlbnRydXN0LmNvbS9yb290cy9kc3Ryb290Y2F4My5wN2MwHwYDVR0jBBgwFoAUxKexpHsscfrb4UuQdf_EFWCFiRAwVAYDVR0gBE0wSzAIBgZngQwBAgEwPwYLKwYBBAGC3xMBAQEwMDAuBggrBgEFBQcCARYiaHR0cDovL2Nwcy5yb290LXgxLmxldHNlbmNyeXB0Lm9yZzA8BgNVHR8ENTAzMDGgL6AthitodHRwOi8vY3JsLmlkZW50cnVzdC5jb20vRFNUUk9PVENBWDNDUkwuY3JsMB0GA1UdDgQWBBSoSmpjBH3duubRObemRWXv86jsoTANBgkqhkiG9w0BAQsFAAOCAQEA3TPXEfNjWDjdGBX7CVW-dla5cEilaUcne8IkCJLxWh9KEik3JHRRHGJouM2VcGfl96S8TihRzZvoroed6ti6WqEBmtzw3Wodatg-VyOeph4EYpr_1wXKtx8_wApIvJSwtmVi4MFU5aMqrSDE6ea73Mj2tcMyo5jMd6jmeWUHK8so_joWUoHOUgwuX4Po1QYz-3dszkDqMp4fklxBwXRsW10KXzPMTZ-sOPAveyxindmjkW8lGy-QsRlGPfZ-G6Z6h7mjem0Y-iWlkYcV4PIWL1iwBi8saCbGS5jN2p8M-X-Q7UNKEkROb3N6KOqkqm57TH2H3eDJAkSnh6_DNFu0Qg)

ISC license
-----------

ASN.1 JavaScript decoder Copyright (c) 2008-2023 Lapo Luchini <lapo@lapo.it>

Permission to use, copy, modify, and/or distribute this software for any purpose with or without fee is hereby granted, provided that the above copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

credits
-------

- OBJECT IDENTIFIER values are recognized using data taken from Peter Gutmann's [dumpasn1](https://www.cs.auckland.ac.nz/~pgut001/#standards) program.
- BMPString support added by [Felipe Gasper](https://github.com/FGasper)
- extended tag support added by [Péter Budai](https://www.peterbudai.eu/)
- patches by [Gergely Nagy](https://github.com/ngg)
- Relative OID support added by [Mistial Developer](https://github.com/mistial-dev)
- dark mode support added by [Oliver Burgmaier](https://github.com/olibu/)
- patches by [Nicolai Søborg](https://github.com/NicolaiSoeborg)

links
-----
- [asn1js-diff on GitHub Pages](https://kshekhovtsova.github.io/asn1js-diff/)
- [official website](https://lapo.it/asn1js/)
- [dedicated domain](https://asn1js.eu/)
- [InDefero tracker](http://idf.lapo.it/p/asn1js/)
- [GitHub mirror](https://github.com/lapo-luchini/asn1js)
- [Ohloh code stats](https://www.openhub.net/p/asn1js)
