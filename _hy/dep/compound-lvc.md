---
layout: relation
title: 'compound:lvc'
shortdef: 'light compound verb'
udver: '2'
---

This subtype of `compound` covers light verbs in Armenian.

~~~ sdparse
Նա միայն բաց արեց պատուհանները ։ \n He only open did the-windows .
compound:lvc(բաց, արեց)
compound:lvc(open, did)
~~~

~~~ sdparse
վեր - վեր թռչել \n high - high to-jump
compound:lvc(վեր-1, թռչել)
compound:lvc(high-6, to-jump)
compound:redup(վեր-1, վեր-3)
compound:redup(high-6, high-8)
punct(վեր-3, --2)
punct(high-8, --7)
~~~

~~~ sdparse
թույլ տալ \n permission to-give
compound:lvc(թույլ, տալ)
compound:lvc(permission, to-give)
~~~
