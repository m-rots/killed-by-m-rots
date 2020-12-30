+++
title = "Dash"
date = 2019-03-01

[extra]
killed = "March 2019"
+++

While working on Holo (R.I.P.), one of the major components I wanted to add was a service-account-based uploader for unlimited file uploading. Naive as I was back then, Dash had to generate money. Therefore, the first version of Dash was partially a cloud service. Not only to make a revenue, but also to track the status of service-accounts across machines.

An important feature of Dash was its ability to prevent file duplication, an issue which was present in RClone in 2019. For this to work, it had to cache the Google Drive metadata locally. This caching was far from perfect and was later massively improved with Bernard, however, Dash was buried by then.

As the cloud model did not work for Dash, the project was later revived two times. The first revive was written in TypeScript and was aiming for a self-hosted server model which the CLI communicated with. However, it did not make it past the prototype stage. The second revive was written in Go and made use of the Bernard backend. However, no upload-related code was written as I lost interest before even starting.

<!-- more -->