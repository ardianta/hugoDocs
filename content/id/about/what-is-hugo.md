---
title: Apa itu Hugo?
linktitle: Apa itu Hugo?
description: Hugo adalah generator web statis yang cepat dan modern, ditulis dengan bahasa Go dan dirancang untuk membuat website dengan cara menyenangkan.
date: 2017-02-01
publishdate: 2017-02-01
lastmod: 2017-02-01
layout: single
menu:
  docs:
    parent: "about"
    weight: 10
weight: 10
sections_weight: 10
draft: false
aliases: [/overview/introduction/,/about/why-i-built-hugo/]
toc: true
---

Hugo adalah sebuah framework untuk membuat web. Bahasa teknisnya, Hugo adalah sebuah
generator web statis ([static site generator][]). Tidak seperti sistem konvensional
yang membuat halaman web secara dinamis saat tiap pengunjung membukanya, Hugo
akan membuat halaman web saat anda membuat atau mengubah konten. Karena website lebih
sering dibuka daripada diedit, Hugo dirancang untuk menyediakan pengoptimalan pengalaman
saat pengunjung membuka website dan pengalaman menulis yang ideal untuk penulis konten.

<!-- Hugo is a general-purpose website framework. Technically speaking, Hugo is a [static site generator][]. Unlike systems that dynamically build a page with each visitor request, Hugo builds pages when you create or update your content. Since websites are viewed far more often than they are edited, Hugo is designed to provide an optimal viewing experience for your website's end users and an ideal writing experience for website authors. -->

Website yang dibuat dengan Hugo sangat cepat dan aman dan bisa di-hosting
di mana saja, di [Netlify][], [Heroku][], [GoDaddy][], [DreamHost][], [GitHub Pages][], [GitLab Pages][], [Surge][], [Aerobatic][], [Firebase][], [Google Cloud Storage][], [Amazon S3][], [Rackspace][], [Azure][], dan [CloudFront][] dan juga bisa pada CDN. Website yang dibuat dengan Hugo dapat berjalan meski tanpa database atau runtime yang mahal seperti Ruby, Python, or PHP.

<!-- Websites built with Hugo are extremely fast and secure. Hugo sites can be hosted anywhere, including [Netlify][], [Heroku][], [GoDaddy][], [DreamHost][], [GitHub Pages][], [GitLab Pages][], [Surge][], [Aerobatic][], [Firebase][], [Google Cloud Storage][], [Amazon S3][], [Rackspace][], [Azure][], and [CloudFront][] and work well with CDNs. Hugo sites run without the need for a database or dependencies on expensive runtimes like Ruby, Python, or PHP. -->

Menurut kami, Hugo merupakan sebuah alat yang ideal untuk membuat website dengan
kecepatan *build* yang instan dan memungkinkan untuk membangun ulang (rebuild) apapun
perubahan yang telah dilakukan.

<!-- We think of Hugo as the ideal website creation tool with nearly instant build times, able to rebuild whenever a change is made. -->

## Seberapa Cepat Hugo?

{{< youtube "CdiDYZ51a2o" >}}

## Bagaimana Cara Kerja Hugo?

Dalam bahasa teknis, Hugo membaca direktori sumber yang berisi file dan template.
Lalu menggunakannya sebagai input untuk membuat website.

<!-- In technical terms, Hugo takes a source directory of files and templates and uses these as input to create a complete website. -->

## Siapa yang Harus menggunkan Hugo?

Hugo untuk orang yang lebih senang menulis di teks editor daripada web browser.

Hugo untuk orang yang ingin menulis sendiri kode websitenya tanpa harus khawatir
tentang runtime yang kompleks dan database.

Hugo cocok untuk orang yang suka membuat blog, web company profile,
web portofolio, web dokumentasi, landing page, atau sebuah web
dengan ribuan halaman.

<!-- Hugo is for people that prefer writing in a text editor over a browser.

Hugo is for people who want to hand code their own website without worrying about setting up complicated runtimes, dependencies and databases.

Hugo is for people building a blog, a company site, a portfolio site, documentation, a single landing page, or a website with thousands of pages. -->



[@spf13]: https://twitter.com/@spf13
[Aerobatic]: https://www.aerobatic.com/
[Amazon S3]: https://aws.amazon.com/s3/
[Azure]: https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website
[CloudFront]: https://aws.amazon.com/cloudfront/ "Amazon CloudFront"
[DreamHost]: https://www.dreamhost.com/
[Firebase]: https://firebase.google.com/docs/hosting/ "Firebase static hosting"
[GitHub Pages]: https://pages.github.com/
[GitLab Pages]: https://about.gitlab.com/features/pages/
[Go language]: https://golang.org/
[GoDaddy]: https://www.godaddy.com/ "Godaddy.com Hosting"
[Google Cloud Storage]: https://cloud.google.com/storage/
[Heroku]: https://www.heroku.com/
[Jekyll]: https://jekyllrb.com/
[Middleman]: https://middlemanapp.com/
[Nanoc]: https://nanoc.ws/
[Netlify]: https://netlify.com
[Rackspace]: https://www.rackspace.com/cloud/files
[Surge]: https://surge.sh
[contributing to it]: https://github.com/gohugoio/hugo
[rackspace]: https://www.rackspace.com/cloud/files
[static site generator]: /about/benefits/
