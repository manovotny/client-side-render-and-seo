# client-side-render-and-seo

> A client side rendered React site to test how seo does.

Created using [create-react-app](https://github.com/facebookincubator/create-react-app).

## Research

Below are some articles I found supporting the idea that client side rendered apps are perfectly indexable by search engines.

* [Will Google find your React content?](http://andrewhfarmer.com/react-seo/)
* [SEO vs. React: Web Crawlers are Smarter Than You Think](https://medium.freecodecamp.org/seo-vs-react-is-it-neccessary-to-render-react-pages-in-the-backend-74ce5015c0c9)

## Results

[Google does seem to index this repository's GitHub Pages site](https://www.google.com/search?q=site%3Ahttps%3A%2F%2Fmanovotny.github.io%2Fclient-side-render-and-seo%2F&oq=site%3Ahttps%3A%2F%2Fmanovotny.github.io%2Fclient-side-render-and-seo%2F&gs_l=serp.3...0.0.0.259593.0.0.0.0.0.0.0.0..0.0....0...1..64.serp..0.0.0.w1H7UpdEAs4) just fine, content and all!

On the downside, [Yahoo doesn't seem to be able to find the site](https://search.yahoo.com/search;_ylt=A0LEV0pfeDVZTugA0nFXNyoA;_ylc=X1MDMjc2NjY3OQRfcgMyBGZyA3lmcC10BGdwcmlkA2NTTU9mVjZoVFlPNG1xdnlTMDhRT0EEbl9yc2x0AzAEbl9zdWdnAzAEb3JpZ2luA3NlYXJjaC55YWhvby5jb20EcG9zAzAEcHFzdHIDBHBxc3RybAMwBHFzdHJsAzcyBHF1ZXJ5A3NpdGUlM0FodHRwcyUzQSUyRiUyRm1hbm92b3RueS5naXRodWIuaW8lMkZjbGllbnQtc2lkZS1yZW5kZXItYW5kLXNlbyUyRgR0X3N0bXADMTQ5NjY3NjQ5MA--?p=site%3Ahttps%3A%2F%2Fmanovotny.github.io%2Fclient-side-render-and-seo%2F&fr2=sb-top&fr=yfp-t&vm=r&fp=1) at all. [Bing doesn't either](https://www.bing.com/search?q=site%3Ahttps%3A%2F%2Fmanovotny.github.io%2Fclient-side-render-and-seo%2F&qs=n&form=QBRE&sp=-1&pq=site%3Ahttps%3A%2F%2Fmanovotny.github.io%2Fclient-side-render-and-seo%2F&sc=0-60&sk=&cvid=414EF59C0ACF43268DA19FA792BD8BA9&adlt=strict) (which makes sense because Yahoo uses Bing behind the scenes). But I honestly think this is due to Yahoo / Bing crawling GitHub Pages sites poorly. I bet they'd pick up the site just fine if I used a regular domain. Case and point, [Yahoo / Bing index react router's site](https://www.bing.com/search?q=site%3Ahttps%3A%2F%2Freacttraining.com%2Freact-router%2F&qs=n&form=QBLH&sp=-1&pq=site%3Ahttps%3A%2F%2Freacttraining.com%2Freact-router%2F&sc=0-44&sk=&cvid=649238F6C7E14ACA9A2225C141875461) just fine and it's a completely client side rendered site.

So TL;DR, I think client side rendered sites are perfectly fine in regards to search engine crawling.

